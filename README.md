We import the OpenCV library for working with video.
We initialize the camera using cv2.VideoCapture.
We create a background subtractor to identify the moving objects.
Inside the loop, we capture video frames and apply background subtraction to detect changes between frames.
We threshold the foreground mask to create a binary image.
We find contours in the binary image and draw rectangles around the detected motion areas.
The code displays the video feed and highlights areas with motion.
Press the 'Esc' key to exit the program.
Make sure you have OpenCV installed. You can install it with pip: pip install opencv-python

