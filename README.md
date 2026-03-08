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
<img width="983" height="724" alt="image" src="https://github.com/user-attachments/assets/6bed69b3-9437-4c2a-86b6-0f439467068f" />
<img width="797" height="653" alt="image" src="https://github.com/user-attachments/assets/ea838ba3-7076-4b79-90f8-04ff91fc8842" />
<img width="813" height="577" alt="image" src="https://github.com/user-attachments/assets/17185500-894a-4df3-b4d1-bd134a262a2f" />
<img width="757" height="691" alt="image" src="https://github.com/user-attachments/assets/f4a2a4e9-4597-4417-879a-f7535342ac8d" />
<img width="835" height="621" alt="image" src="https://github.com/user-attachments/assets/2f8a5e0a-3205-4121-93d2-16cb96bb45f6" />
<img width="951" height="693" alt="image" src="https://github.com/user-attachments/assets/017007a1-f32a-4af6-b2f2-8fa730a6bc6f" />


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
