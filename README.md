# AirCanvas-With-ML
This project implements an interactive drawing application that utilizes advanced computer vision techniques to recognize hand gestures in real-time, allowing users to draw on a digital canvas seamlessly. Built using OpenCV for video processing and Mediapipe for hand landmark detection, this application provides a responsive and intuitive user interface for creative expression. The project incorporates elements of machine learning to enhance gesture recognition accuracy, enabling a more reliable interaction model.


# ALGORITHM:

Initialization: Import libraries and set up color point deques and variables.

Canvas Setup: Create a blank canvas and draw color selection buttons.

Webcam Capture: Initialize and capture frames from the webcam in a loop.

Frame Processing: Flip the frame vertically and convert it to RGB format.

Hand Landmark Detection: Use Mediapipe to detect hand landmarks and extract coordinates.

Gesture Recognition: Identify gestures to select colors, clear the canvas, or draw.

Drawing on Canvas: Draw lines between stored points on both the canvas and frame.

Display Output: Show the processed frame and the canvas in separate windows.

Cleanup: Release the webcam and close all OpenCV windows upon exit.
