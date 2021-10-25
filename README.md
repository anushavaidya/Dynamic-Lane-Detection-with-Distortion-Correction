# Dynamic-Lane-Detection-with-Distortion-Correction

This repo demonstrates finding lane lines for curved roads using Computer Vision.

## Pipeline:

The pipeline is as follows:
* Find the distortion parameters of the camera to undistort an image 
* Apply Color and Gradient Thresholding to generate a binary image 
* Apply perspective transform to gain a birds-eye-view 
* Finding the lane lines with the help of Histogram and Sliding Window approach
* Find the curvature of the road 



## What you will need to run:
* Python
* OpenCV
* Numpy
* Pandas 
* Pickle 
* Matplot lib 

## How to run:

Open the jupyter notebook file named `LaneDetction.ipynb` and run all the cells.


