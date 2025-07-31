# 💤 Driver Drowsiness Detection System

A real-time driver monitoring system that detects signs of drowsiness using computer vision techniques.  
Built with Python, OpenCV, and machine learning, the system alerts drivers through an audible alarm when signs of fatigue are detected—helping prevent accidents caused by microsleep or eye closure.

---

## 🔧 Features

- **Eye Detection**: Monitors eye status (open/closed) using Haar cascades.
- **Drowsiness Detection**: Tracks duration of eye closure to detect drowsiness.
- **Audio Alert**: Triggers a buzzer when the driver’s eyes remain closed beyond a threshold.
- **Real-Time Monitoring**: Processes live webcam feed for continuous analysis.

---

## 🛠️ Tech Stack

- Python 3  
- OpenCV  
- Haar Cascade Classifiers  
- NumPy  
- Pygame (for buzzer/alarm)

---

## 🚀 How It Works

1. Capture video stream from webcam.
2. Use Haar cascades to detect face and eye regions.
3. Measure duration of eye closure over consecutive frames.
4. If closed eyes exceed threshold, trigger a loud audio alert.
5. Resume monitoring after alert is acknowledged.

---

