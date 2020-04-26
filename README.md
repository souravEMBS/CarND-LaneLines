Overview
---

When we drive, we use our eyes to decide where to go.  The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle.  Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.

In this project you will detect lane lines in images using Python and OpenCV.

Proposed Solution
---
* Start with an image or frame from a video clip

<img src="test_images/solidWhiteCurve.jpg" width="480" alt="Combined Image" />

* Convert the image to grayscale

<img src="test_image_output/gray_solidWhiteCurve.jpg" width="480" alt="Combined Image" />

* Apply Gaussian smoothing

<img src="test_image_output/gaussian_solidWhiteCurve.jpg" width="480" alt="Combined Image" />

* Apply Canny edge detection function

<img src="test_image_output/canny_solidWhiteCurve.jpg" width="480" alt="Combined Image" />

* Create mask on image to define working region

<img src="test_image_output/mask_solidWhiteCurve.jpg" width="480" alt="Combined Image" />

* Apply Hough transform on the selected region

<img src="test_image_output/hough_solidWhiteCurve.jpg" width="480" alt="Combined Image" />


* Draw lines on top of original image


<img src="test_image_output/combo_solidWhiteCurve.jpg" width="480" alt="Combined Image" />



Outcome
---

The results can be seen in this [video](test_videos_output/solidWhiteRight.mp4)