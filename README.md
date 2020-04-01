# **Finding Lane Lines on the Road** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

<img src="examples/laneLines_thirdPass.jpg" width="480" alt="Combined Image" />

Overview
---
<!--- Purpouse?
When we drive, we use our eyes to decide where to go.  The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle.  Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.-->

This project implements a pipeline to detect lane lines in images using Python and OpenCV.

Content
---
This repository contains:

1. A jupyuter notebook with the code.
<!---2. An HTML file with code already runned??-->

2. A writeup, which describes the pipeline in detail and identifies shortcomings while suggesting possible improvements.

3. 4 folders with the images and videos used to tune and test the pipeline and the correspondant outputs.

<!-- pipeline??-->

Usage
---
<!-- Dependencies-->
**Step 1:** Download the repository `> git clone https://github.com/stecasta/lane-detection.git`

**Step 2:** Open the Jupyter notebook in your browser. `> jupyter notebook`

**Step 3:** A browser window will appear showing the contents of the current directory.  Click on the file called "P1.ipynb".  Another browser window will appear displaying the notebook.  Follow the instructions in the notebook.

If you want to process your own video, place it in the `test_videos` folder and edit the line `white_output = 'test_videos_output/solidWhiteRight.mp4'` by putting the name of your video.

License
---

This project is licensed under the terms of the [MIT license](https://opensource.org/licenses/MIT).
