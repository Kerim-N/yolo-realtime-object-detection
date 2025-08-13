# 🎯 Real-Time Object Detection with YOLOv8

This Python script allows **real-time object detection** using a webcam and the **Ultralytics YOLOv8** model. It can detect multiple objects in a video stream, display bounding boxes with labels, and optionally show FPS.

## 🚀 Features
- **Real-time detection** from webcam or other video sources.
- Supports **any YOLOv8 model** (`n`, `s`, `m`, `l`, `x`, or custom `.pt` files).
- Runs on **CPU** or **GPU (CUDA)** automatically.
- Displays **confidence scores** and **object class names**.
- Optional **FPS counter** for performance monitoring.
- Easy customization via command-line arguments.

---

## 📦 Requirements

Make sure you have Python **3.8+** installed.  
Then install dependencies:

```bash
pip install opencv-python ultralytics torch
