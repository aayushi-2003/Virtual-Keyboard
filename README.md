# Virtual Keyboard using OpenCV and MediaPipe
This project implements a virtual keyboard using OpenCV and MediaPipe libraries in Python. It allows users to interact with a virtual keyboard interface using hand gestures captured through a webcam.

## Features

1. Hand Tracking: Utilizes the MediaPipe library to detect and track the user's hand movements in real-time.
2. Virtual Keyboard Interface: Displays a graphical virtual keyboard on the screen.
3. Hand-Gesture Interaction: Users can control the virtual keyboard by performing hand gestures recognized by the system.

## Modules
1. handtracking.py
This module contains the implementation of hand tracking functionality using the MediaPipe library. It provides methods to detect and track the user's hand landmarks in real-time video streams from a webcam.

2. virtualkeyboard.py
The virtualkeyboard.py module implements the virtual keyboard interface using OpenCV. It utilizes the hand tracking module to enable users to interact with the keyboard using hand gestures.

## Requirements
1. Python 3.8
2. OpenCV
3. MediaPipe

## Installation
Install the required dependencies:
```sh
pip install opencv-python mediapipe
```

## Usage
1. Run the virtualkeyboard.py script:
``` sh
python virtualkeyboard.py
```
2. Ensure your webcam is connected and properly configured.
3. Interact with the virtual keyboard by using your index finger to point and select, and both your index finger and middle finger close up to perform a button click.




