# Driver Drowsiness Detection

This project is a real-time driver drowsiness detection system built with Flask, OpenCV, and dlib.  
It monitors the driver’s eyes through a webcam and triggers alerts if drowsiness is detected.

## Features
- Detects drowsiness using Eye Aspect Ratio (EAR).
- Plays an audio alert when the driver appears drowsy.
- Sends a Telegram message alert via a bot.
- Live video stream available in a web browser (Flask server).

## Requirements
click==8.1.7  
Flask==2.1.3  
itsdangerous==2.1.2  
Jinja2==3.1.3  
MarkupSafe==2.1.3  
Werkzeug==3.0.1  

Also required:  
- opencv-python  
- dlib  
- pygame  
- imutils  
- scipy  
- requests  

## Setup & Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/drowsiness-detection.git
cd drowsiness-detection

# Install dependencies
pip install -r requirements.txt
