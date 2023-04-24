# Lane-Line-Detection-
Detection of lane lines on a road using OpenCV library of Python.
We use a test video of a self-driving car moving on a road and import this video in our program.
We extract each frame from the video and perform our operations on each of those frames.
The process goes on as long as there is a frame to be extracted from the video.
We perform Gray Scaling and apply Gaussian Blur on each frame and then apply Canny Edge Detection on them.
The region of interest is mapped out on the canny image.
Hough Transform is applied on those frames and the lane lines are extrapolated.
The final frame is the one we get after combining the original frame and the one with the lane lines in it.
This entire process is applied on the video stream.
The user, if not interested in watching the entire video stream, is given the option of ending the video prematurely if they wish to by pressing 'a' on the keyboard.
