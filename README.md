# Detecting-road-
Detecting the Road lanes using OpenCV
•	Imported the required libraries
•	Imported the test image in an array.
•	Changed the color of the image from RGB to Grayscale for less intensity.
•	Filtered the image noise, which can create false edges and ultimately affect edge detection.
•	Used Gaussian blur to smoothened the image.
•	Used the Edge Detection algorithm canny, which identifies the boundaries of objects within the images. And also to outline the strongest gradients in the image. 
•	Used Matplolib to identify the region of interest.
•	Created a polygon on the region of interest and masked the polygon using fill_poly and numpy.
•	Used Hough-Transform algorithm to detect the straight lines in the image.
•	Detected the straightlines by changing the intensity of the lines to blue over a black background.
•	Finally, Blended the line image on top of the original image.
•	Then, averaged the left line coordinates and the right line coordinates for a perfect fit.
•	Further imported the mp4 video of the lane and gave the same written algorithm.
•	It detects the lanes as was seen in the image.
