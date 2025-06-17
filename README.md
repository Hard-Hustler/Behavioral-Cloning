
# 🚗 Behavioral Cloning for Self-Driving Cars using YOLOv11

This project implements a **behavioral cloning** system for autonomous vehicles using the **YOLOv11** architecture. It combines the power of real-time object detection with driver behavior imitation to create an efficient driving agent trained end-to-end.

## 📝 Project Overview

Behavioral cloning is a form of supervised learning where a model learns to mimic human driving behavior from recorded driving data. This notebook demonstrates how to:

- Use YOLOv11 (You Only Look Once v11) for real-time perception
- Clone driver behavior by predicting steering angles from camera images
- Train and evaluate models on a driving simulator dataset
- Visualize predictions to understand decision-making

### Features

- End-to-end driving model using deep CNN + YOLOv11
- Real-time frame capture and prediction visualization
- Dataset preprocessing and augmentation
- Steering angle prediction and overlay

### Dataset
You can use:

- Udacity Self-Driving Car Simulator for data collection.
- Custom real-world driving datasets for further experimentation.

### Results
- Model achieves smooth lane-following on simulator test tracks
- Successfully generalizes to unseen curves and lighting
- Example plots and prediction overlays included in the notebook


## 📁 Folder Structure
```bash
.
├── behavioural-cloning-yolov11.ipynb   # Main notebook with training + results
├── dataset/                            # Input images and driving log
├── models/                             # Saved YOLO weights or custom models
└── README.md                           # Project documentation
```
## Authors

**Hardik Amarwani**

- Email: [hardikamarwani@gmail.com](mailto:hardikamarwani@gmail.com)
- Github: [github.com/Hard-Hustler](https://github.com/Hard-Hustler)

**Aayush Kanungo**

- Email: [aayushkanungo02@gmail.com](mailto:aayushkanungo02@gmail.com)
- Github: [github.com/aayushkanungo02](https://github.com/aayushkanungo02)

