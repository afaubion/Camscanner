# Camscanner
A basic Camscanner application written with OpenCV python.

The Camscanner app was built and created in accordance with this youtube tutorial:
https://www.youtube.com/watch?v=PV0uxIfy_-A
This video contains a tutorial for creating the Camscanner app and a demo of the application.

This Camscanner applicaiton works by:
1. Taking an image as input
2. Scans the document from the image utilizing multiple image processing techniques (more details below)
3. Outputs the image with the scanned effects

More detail:
1. Resize the image so OpenCV can work with said image
2. Gaussian blur to smooth the image
3. Canny edges to detect edges of document in image
4. Locate the contours and boundaries of the pages
5. Map to an 800x800 sized window
6. Apply perspective trasform to get scanned image

To install application, must install OpenCV python
To do this, type in terminal:

pip install opencv-python


