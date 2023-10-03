# Canny Edge Detection Step by Step
This code is based on the Canny Edge Detection algorithm which is a widely-used technique in computer vision and image processing to identify edges in images. It involves several steps, including Gaussian blurring, gradient calculation using the Sobel filter, non-maximum suppression, double thresholding, and hysteresis to produce a final edge-detected image. 

## Libraries
- numpy
- OpenCV
- matplotlib

## Code Structure
- **Gaussian Blur (Gaussian_blur)** <br>
Applies Gaussian blur to the input grayscale image to reduce noise

- **Sobel Filter (Sobel_filter)** <br>
Computes the gradient of the image using the Sobel filter in both the x and y directions

- **Non-Maximum Suppression (non_max_suppression)** <br>
Suppresses non-maximum values in the gradient image based on gradient directions

- **Double Thresholding (double_threshold)** <br>
Applies double thresholding to identify potential edge pixels as strong or weak

- **Hysteresis (edge_tracking_by_hysteresis)** <br>
Performs edge tracking by connecting weak edges to strong edges

- **Canny Edge Detector (canny_edge_detector)** <br>
Combines all the previous steps to produce the final edge-detected image

