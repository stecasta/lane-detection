# **Finding Lane Lines on the Road** 


The goals of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on the work in a written report


[//]: # (Image References)

[image0]: ./test_images/solidYellowLeft.jpg "original"
[image1]: ./test_images_output/1_gray.jpg "gray"
[image2]: ./test_images_output/2_gauss.jpg "blurred_gray"
[image]: ./test_images_output/3_canny.jpg "canny"
[image4]: ./test_images_output/4_ROI.jpg "roi"
[image5]: ./test_images_output/5_hough.jpg "hough"
[image6]: ./test_images_output/6_scattered.jpg "scattered"
[image7]: ./test_images_output/7_final.jpg "final"


---

### Reflection

### 1. Pipeline Description.

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I applied a Gaussian filter. I fed this image to the canny detection algorithm and then selected a region of interest on the output. Afterwards, I used the Hough Transform function and finally, I extrapolated the two lanes from the hough lines and drew them on the original image.

In order to draw a single line on the left and right lanes, I wrote a function `fit_lanes` which takes the hough lines and the approximate point of separation of the lanes in the image and returns the slope and intercept of the two lanes. This function first divides the points based on their position in the image and then applies to them a linear regression with the function `np.polyfit`.

Here is an example of how the pipeline works on the "solidYellowLeft" image: 

![alt text0][image0] ![alt text1][image1]

![alt text2][image2]
![alt text3][image3]
![alt text4][image4]
![alt text5][image5]
![alt text6][image6]
![alt text7][image7]


### 2. Potential Shortcomings of Current Pipeline.

-lane changing, camera in different position, different light conditions(fixed thresholds)
One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


### 3. Possible Improvements to Current Pipeline

A possible improvement would be to ...

Another potential improvement could be to ...
