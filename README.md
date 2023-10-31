# Volume_gesture_control-
This repository includes a computer vision algorithm to contol pc's volume by the movement of the hand. 

# Overview:
This Python script utilizes OpenCV and MediaPipe libraries to enable real-time hand tracking and gesture-based volume control on a computer. The script tracks specific landmarks on the hand, calculates the distance between them, and adjusts the system's audio volume accordingly. Additionally, it provides a visual representation of the volume percentage and frames per second (FPS) on the video feed.

# Setup:

Install the required libraries by running: pip install opencv-python mediapipe numpy comtypes

Ensure that you have a working webcam connected to your computer.

Run the script by executing the following command in the terminal or command prompt: python script_name.py (replace script_name.py with the actual script filename).

# Dependencies:

OpenCV: Computer vision library for image and video processing.
MediaPipe: Library for hand tracking and pose estimation.
NumPy: Library for numerical operations.
comtypes: Module for handling COM interfaces in Windows.
[Optional] pycaw: Library for interacting with the Windows Core Audio API. Install it with pip install pycaw if not already installed.

# Usage:

Upon running the script, it will access the webcam and display the video feed.
The distance between specific landmarks on your hand controls the system volume.
The script provides a visual representation of the volume percentage and FPS on the video feed.
Press 'q' to terminate the script.

# Customization:

Adjust the webcam dimensions by modifying the wCam and hCam variables in the script.
Customize the hand tracking and volume control parameters as needed.

# Note:

This script is designed for Windows systems due to its reliance on the pycaw library for audio control.
Ensure that your system has the necessary permissions to control audio settings.
