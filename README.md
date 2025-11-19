# Firearm Detection using Artificial Intelligence 🔍🔫

This repository contains the implementation of **Firearm Detector**, an AI-powered system
for **real-time firearm detection** using **deep learning** and **computer vision**.

The project was developed as a final year B.Tech project by  
**Sanskar Bhatkar (MITU22BTCS0728)** and **Mayank Pande (MITU22BTCS0433)**  
under the guidance of **Prof. Rashmi Tuptewar** at **MIT School of Computing, MIT ADT University, Pune**.

---

## 🎯 Project Overview

In an era of rising public safety concerns, traditional CCTV systems rely on human operators,
which can lead to delays and missed threats. **Firearm Detector** automates the process by:

- Analyzing video streams in real time  
- Detecting firearms using deep learning  
- Generating instant alerts for quick response  

The system is designed for environments like **schools, airports, malls, offices** and can be
integrated into **smart city surveillance systems**.

---

## 🧠 Core Technologies

- **Deep Learning**: Convolutional Neural Networks (CNNs)
- **Object Detection Frameworks**:
  - **YOLO** (You Only Look Once)
  - **Faster R-CNN**
- **Programming Language**: Python
- **Libraries / Tools** (example):
  - PyTorch / TensorFlow
  - OpenCV
  - NumPy
  - Matplotlib / Seaborn

> You can adjust this list based on what you actually used.

---

## 🏗️ Architecture (High-Level)

1. **Data Acquisition & Preprocessing**
   - Collect weapon image/video datasets
   - Annotation with bounding boxes
   - Data augmentation (rotation, flip, color jitter)

2. **Model Training**
   - Use YOLO / Faster R-CNN for object detection
   - Train on annotated firearm datasets
   - Optimize accuracy and reduce false positives

3. **Model Deployment**
   - Load trained model
   - Process video frames in real time
   - Run inference to detect firearms

4. **Alert System**
   - Draw bounding boxes and labels on frames
   - Trigger alerts (console logs / GUI / API hook)

---

## 📦 Project Structure

```text
firearm-detector/
├── src/
│   ├── detection.py        # Main detection script
│   ├── train.py            # Model training script
│   └── utils.py            # Helper functions
├── models/                 # Model weights or configs
├── notebooks/              # Optional Jupyter notebooks
├── docs/                   # Report, images, diagrams
├── requirements.txt        # Python dependencies
└── README.md
