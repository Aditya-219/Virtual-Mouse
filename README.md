# Virtual Mouse

This Python project implements a virtual mouse using hand tracking. The system utilizes the OpenCV library for computer vision, NumPy for numerical operations, and Autopy for mouse control.

## Features

- Hand tracking to detect hand gestures and movements.
- Control the mouse cursor using hand movements.
- Perform left-click by bringing the index finger and thumb close together.
- Display real-time frames per second (FPS) on the screen.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Autopy

## Install the required libraries:

   ```bash
   pip install opencv-python numpy autopy
   ```


1. Run the virtual_mouse.py script:

    ```bash
    python virtual_mouse.py
    ```

2. Place your hand in front of the camera to control the mouse.

3. Adjust finger gestures as specified in the code comments.

4. Enjoy controlling your computer's mouse with hand movements.

## Code Explanation

- handtracking.py: Module for hand tracking using OpenCV.
- virtual_mouse.py: Main script importing the hand tracking module.
    - Captures video feed from the webcam.
    - Tracks hand and finger positions.
    - Maps hand movements to mouse cursor.
    - Implements left-click functionality based on finger proximity.
    - Displays real-time FPS on the screen.

## Acknowledgments

The hand tracking module used in this project is based on the HandTracking library.
