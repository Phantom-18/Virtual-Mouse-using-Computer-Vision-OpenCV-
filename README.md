# Virtual Mouse using OpenCV, MediaPipe & PyAutoGUI

This project implements a Virtual Mouse that allows you to control your computer cursor using hand gestures via your webcam. By leveraging OpenCV for image processing, MediaPipe for real-time hand tracking, and PyAutoGUI for system control, the program lets you move the cursor with your index finger and perform clicks with a simple thumb–index gesture.

Features:-

1. Cursor Control – Move the mouse pointer using your index finger.
2. Click Gesture – Perform a mouse click when your thumb and index finger come close.
3. Real-time Hand Tracking – Uses Google’s MediaPipe for high-accuracy landmark detection.
4. Cross-Platform – Works on Windows, macOS, and Linux (requires Python support).

Tech Stack:-

1. Python 
2. OpenCV – Video capture & image processing
3. MediaPipe – Hand detection & landmark tracking
4. PyAutoGUI – Mouse control automation

How It Works:-

1. Start the webcam stream with OpenCV.
2. MediaPipe detects hand landmarks in real-time.
3. The index finger tip (id=8) controls the mouse position.
4. If the thumb tip (id=4) comes near the index finger, it triggers a mouse click.

Usage:-

git clone https://github.com/your-username/virtual-mouse.git cd virtual-mouse pip install -r requirements.txt python virtual_mouse.py

1. Move your index finger to control the cursor.
2. Bring your thumb close to your index finger to perform a click.
3. Press 'q' to quit.
