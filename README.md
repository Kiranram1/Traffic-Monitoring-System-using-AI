# 🚦 Traffic Monitoring System using YOLO & Deep SORT  

![Computer Vision](https://img.shields.io/badge/ComputerVision-YOLOv8-blue?logo=opencv)  
![Python](https://img.shields.io/badge/Python-3.10+-yellow?logo=python)  
![DeepSORT](https://img.shields.io/badge/Tracking-DeepSORT-green)  
![License](https://img.shields.io/badge/License-MIT-red)  

---

## 📌 Overview  
The rapid growth of urbanization has led to **increased vehicular traffic**, making efficient traffic monitoring essential for **road safety and traffic management**.  

This project implements a **real-time traffic monitoring system** that uses **YOLO (You Only Look Once)** for vehicle detection and **Deep SORT (Simple Online and Real-time Tracking)** for multi-object tracking. The system is further extended with **Bird’s Eye View (BEV) transformation** for speed estimation, enabling accurate and scalable traffic surveillance.  

---

## 🚀 Features  
✅ **YOLOv8-based Vehicle Detection** – Robust real-time object detection.  
✅ **Deep SORT Tracking** – Multi-object tracking with reduced ID switches.  
✅ **Bird’s Eye View Transformation** – Corrects perspective distortion for accurate distance measurement.  
✅ **Speed Estimation** – Converts pixel movement into km/h using scaling factors.  
✅ **Scalable Design** – Can be extended for traffic violations & automated ticketing systems.  

---

## 🛠️ Tech Stack  

| Category            | Tools/Frameworks |
|---------------------|------------------|
| **Language**        | ![Python](https://img.shields.io/badge/Python-3.10-yellow?logo=python) |
| **Object Detection**| ![YOLOv8](https://img.shields.io/badge/YOLOv8-blue) |
| **Tracking**        | Deep SORT, Kalman Filter |
| **Computer Vision** | OpenCV |
| **Visualization**   | Matplotlib |
| **Deployment**      | Jupyter Notebook / Python Scripts |

---

## 📂 Methodology  

1. **Object Detection** – YOLOv8 extracts vehicles from video frames.  
2. **Tracking** – Deep SORT with Kalman Filter ensures reliable ID assignment.  
3. **Perspective Transformation (BEV)** – Converts road scene to top-down view.  
4. **Speed Estimation** –  
   - Pixel-based distance calculation.  
   - Conversion to km/h using reference scaling factor.  
5. **Extensions** – Can integrate speed-limit enforcement & automated ticketing.  

---

## 📊 Results  

- Real-time multi-vehicle tracking with minimal ID switches.  
- Accurate speed estimation using BEV transformation.  
- Scalable for smart city traffic monitoring.  

---

## 🔮 Future Enhancements  

- Integration with **traffic violation detection** (e.g., red light jumping, overspeeding).  
- Cloud/Edge deployment for **smart city applications**.  
- Incorporating **license plate recognition** for automated fines.  
- Expanding dataset and testing across multiple camera views.  

---

## 👨‍💻 Authors  

- **Chandan Kumar K R**  
- **Gopinath Ramaje**  
- **Kiran H R**  

