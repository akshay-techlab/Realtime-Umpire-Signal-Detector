# 🏏 Cricket Umpire Signal Detection System

A Computer Vision based system that detects cricket umpire signals such as FOUR, SIX, OUT etc from video input using Python, OpenCV, and MediaPipe.
The project analyzes the umpire’s body pose and arm movements in real time to recognize gestures corresponding to cricket signals.
📌 Features
Real-time umpire signal detection
Uses pose estimation to track body landmarks

Detects gestures like:
FOUR
SIX
OUT
SHORT RUN
WIDE
NO BALL 
DEAD BALL

https://github.com/user-attachments/assets/caa2f2a5-b5e2-473a-a7ad-acc02e185f38

Works with video input or webcam
Lightweight and easy to run
🧠 Technologies Used
Python
OpenCV
MediaPipe
Computer Vision

⚙️ How It Works
Capture video frames using OpenCV.
Detect body landmarks using MediaPipe Pose.
Track arm movement and positions.
Apply gesture recognition logic.
Display detected umpire signal in real time.
