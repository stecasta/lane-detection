# **Finding Lane Lines on the Road** 


The goals of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./test_images/solidYellowLeft.jpg "original"
[image1]: ./test_images_output/1_gray.jpg "gray"
[image1]: ./test_images_output/2_gauss.jpg "blurred_gray"
[image1]: ./test_images_output/3_canny.jpg "canny"
[image1]: ./test_images_output/4_ROI.jpg "roi"
[image1]: ./test_images_output/5_hough.jpg "hough"
[image1]: ./test_images_output/6_scattered.jpg "scattered"
[image1]: ./test_images_output/7_final.jpg "final"


---

### Reflection

### 1. Pipeline Description.

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I .... 

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by ...

If you'd like to include images to show how the pipeline works, here is how to include an image: 

![alt text][image1]


### 2. Potential Shortcomings of Current Pipeline.


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


### 3. Possible Improvements to Current Pipeline

A possible improvement would be to ...

Another potential improvement could be to ...
