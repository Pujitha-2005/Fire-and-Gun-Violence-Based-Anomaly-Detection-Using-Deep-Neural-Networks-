# Gun and Fire Detection using YOLO

## 📌 Overview
This project detects **guns**, **fire**, and **rifles** in real-time video streams or recorded videos using the **YOLO (You Only Look Once)** object detection algorithm.  
It can be used for surveillance, safety monitoring, and emergency alert systems.

---

## 🚀 Features
- Detects:
  - 🔫 Guns
  - 🔥 Fire
  - 🪖 Rifles
- Works with:
  - Webcam live feed
  - Pre-recorded video
  - Image files
- Real-time detection with bounding boxes and labels
- Supports **alert system** integration (e.g., sound alarm or send notifications)

---

## 📂 Project Files
- `yolo.py` → Main script for detection
- `obj.names` → List of object class names (`Gun`, `Fire`, `Rifle`)
- `yolov3.cfg` → YOLO model configuration file
- `yolov4.weights` → Pre-trained YOLO weights for detection


---

## ⚙️ Requirements
Install dependencies before running:
```bash
pip install opencv-python numpy
