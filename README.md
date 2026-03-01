# 😴 Real-Time Fatigue Detection System

A **real-time driver or user fatigue detection system** using **YOLO (Ultralytics)** and **OpenCV**.  
The system detects **closed eyes and closed mouth** to determine if a person is showing signs of fatigue.

---

## 🛠 Technologies Used
- **Python**  
- **Ultralytics YOLO** – Object detection model  
- **OpenCV** – Video capture and visualization  
- **Computer Vision** – Real-time fatigue detection  

---

## ⚡ Features
- Detects signs of fatigue:
  - 👀 **Closed Eye**  
  - 👄 **Closed Mouth**  
- Displays bounding boxes and labels for detected features  
- Shows **status**:
  - 🔴 `FATIGUE DETECTED` when signs of fatigue are detected  
  - 🟢 `NORMAL` when no fatigue signs are detected  
- Works in **real-time with webcam**  

---

## 🧠 How It Works

Load the YOLO model (bestt.pt) trained on fatigue features.

Capture frames from webcam in real-time.

Detect closed eyes and closed mouth in each frame.

Draw bounding boxes and labels on the detected features.

Display status text:

FATIGUE DETECTED if signs of fatigue are detected

NORMAL if no signs of fatigue

## 🔗 References

Ultralytics YOLO

OpenCV Documentation


---

## 💻 How to Run
1. Clone the repository:
```bash
git clone https://github.com/Rou-maissa/Fatigue_detection.git
