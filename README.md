# Length-and-Angle-Measuring-using-OpenCV-
Pencil Detection and Measurement Using OpenCV This project demonstrates a comprehensive approach to detecting and measuring pencils in an image using computer vision techniques. The primary objectives include:  Detecting the contours of pencils in an image. Fitting lines along the length of the pencils.
Pencil Detection and Measurement Using OpenCV
This project demonstrates a comprehensive approach to detecting and measuring pencils in an image using computer vision techniques. The primary objectives include:

Detecting the contours of pencils in an image..
Fitting lines along the length of the pencils.
Calculating the length of each pencil, assuming a scale of 1 pixel = 0.1 mm.
Determining the angle between the detected pencils.
Highlighting the region where the pencils intersect.
Features
Medium Blurring: Reduces noise and smoothens the image to enhance edge detection.
Edge Detection: Uses the Canny edge detection algorithm to identify the edges of the pencils.
Contour Detection: Detects the outlines of the pencils in the image.
Line Fitting: Fits lines to the detected pencil contours to measure their lengths accurately.
Angle Calculation: Determines the angle between the fitted lines of two pencils.
Intersection Highlighting: Identifies and highlights the region where the pencils intersect.
Installation
To run this project, you need to have Python and the following libraries installed:

OpenCV
NumPy
Matplotlib

You can install these libraries using pip:


Clone this repository to your local machine.
Place your input image in the same directory or update the image_path variable in the script with the correct path.
Run the script to process the image and display the results.
