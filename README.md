
# 2D LiDAR and RGB Camera Sensor Fusion for Autonomous Vehicles

## Overview

This project focuses on developing a **2D LiDAR and RGB camera sensor-fusion system** for real-time object detection in autonomous vehicle applications.

The system combines information from **2D LiDAR and RGB camera sensors** to improve the perception of the surrounding environment and support safer autonomous navigation.

## Objectives

* Develop a sensor-fusion framework using 2D LiDAR and RGB camera data.
* Detect and classify objects in an autonomous driving environment.
* Identify **vehicles, pedestrians, cyclists, and obstacles**.
* Improve environmental perception for autonomous vehicle applications.
* Evaluate object detection performance using the KITTI dataset.

## Methodology

The overall workflow is:

**RGB Camera + 2D LiDAR → Data Processing → Sensor Fusion → Object Detection → Object Classification → Vehicle Environment Perception**

### Object Detection

**YOLOv5** was implemented for real-time object detection using the **KITTI dataset**.

The system detects major road users and obstacles, including:

* Vehicles
* Pedestrians
* Cyclists
* Other obstacles

## Dataset

The **KITTI dataset** was used for evaluating the object detection and autonomous driving perception system.

The dataset provides sensor data and annotated objects from real-world driving scenarios.

## Tools & Technologies

* **Python**
* **MATLAB**
* **YOLOv5**
* **2D LiDAR**
* **RGB Camera**
* **KITTI Dataset**
* Sensor Fusion
* Computer Vision
* Object Detection

## Project Workflow

1. Acquire RGB camera and 2D LiDAR data.
2. Pre-process the sensor data.
3. Extract relevant information from both sensors.
4. Fuse information from the LiDAR and camera.
5. Apply YOLOv5 for object detection.
6. Detect vehicles, pedestrians, cyclists, and obstacles.
7. Analyze the detected objects for autonomous vehicle perception.

## Results

The developed system successfully detected major road objects such as **vehicles, pedestrians, cyclists, and obstacles** using the KITTI dataset.

The sensor-fusion approach provides complementary information from camera and LiDAR sensors for improved environmental perception in autonomous vehicle applications.

## Applications

* Autonomous Vehicles
* Advanced Driver Assistance Systems (ADAS)
* Vehicle Perception
* Object Detection
* Road Safety
* Autonomous Navigation

## Repository Structure

```text
2D-LiDAR-RGB-Sensor-Fusion/
│
├── README.md
├── MATLAB/
│   └── MATLAB_code/
│
├── Python/
│   ├── YOLOv5/
│   └── detection/
│
├── Dataset/
│   └── KITTI/
│
├── Results/
│   ├── detection_results/
│   └── plots/
│
└── Figures/
    └── system_workflow.png
```

> **Note:** The complete KITTI dataset is not included in this repository due to its size and dataset distribution considerations.

## Future Work

* Improve sensor calibration and alignment.
* Improve object detection accuracy under different environmental conditions.
* Extend the system to real-time autonomous vehicle hardware.
* Investigate additional sensor-fusion techniques for robust perception.

## Author

**Anoop Kumar Singh**
M.Tech – Advanced Manufacturing and Design
Indian Institute of Technology Jodhpur

**Areas:** Automotive Systems | Autonomous Vehicles | ADAS | Computer Vision | Sensor Fusion
