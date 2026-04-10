# AI Fitness Tracker: Bicep Curl Counter

## Description
A real-time AI fitness tracker that counts left-arm bicep curl repetitions using MediaPipe and OpenCV. It tracks body landmarks, calculates the elbow angle, and determines movement stages (up/down) to accurately count reps through a live webcam feed.

The application runs through a webcam feed and provides live visual feedback, including:
- Real-time pose detection and skeleton visualization  
- Dynamic angle calculation of the elbow joint  
- Automatic repetition counting  
- Exercise stage tracking (Up / Down)  

---

## Features
- Real-time pose estimation  
- Joint angle calculation using NumPy  
- Rep counting logic based on motion thresholds  
- Live UI overlay with OpenCV  
- Lightweight and runs on CPU  

---

## Technologies Used
- Python 3.10  
- MediaPipe 0.10.13  
- OpenCV  
- NumPy  
