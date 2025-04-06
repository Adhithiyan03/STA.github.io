---
title: "IEEE Singapore Autonomous Underwater Vehicle Competition"
excerpt: "Autonomous Underwater Vehicle with Custom 5DOF Manipulator <br/><img src='/STA.github.io/images/image_2_0.jpg'>"
collection: portfolio
---
This project involves developing an autonomous underwater vehicle (AUV) for the IEEE Singapore AUV Competition. The system integrates advanced object detection, collision avoidance, and navigation capabilities.

Key Technical Components:

Object Detection & Collision Avoidance:
- Implemented using YOLOv5 deep learning model
- Pre-trained on COCO128 dataset
- Fine-tuned on custom dataset combining simulated environment data and competition footage
- Enables real-time detection and tracking of competition elements and obstacles

Navigation System:
- Built on ROS Melodic framework for robust inter-component communication
- Utilizes Gazebo UUV simulator for testing in virtual SAUVC arena environment
- Implements sophisticated algorithms including:
  - Kalman Filter-based SLAM for localization and mapping
  - PID and LQR controllers for precise motion control
  - Advanced motion planning for optimal trajectory generation

Electrical System:
- Battery: 2 x LiPo (4s) 14.8 V , 10Ah
- Nominal / Peak current drawn from battery: 98 A/170 A
- CPU + GPU: Nvidia Jetson nano, Quad Core, 4GB RAM
- Microcontrollers: Arduino Mega R3
- DC/DC converter for voltage step up to 16v, step down to 12v and 5v
- Sensors for Navigation: Sensor fusion of Inertial Measurement Unit (IMU) and Doppler Velocity log (DVL), and Depth Sensor.
- Leak Detection using Water detection module and Air pressure sensor module
- Relays 12v/5v and fuses for protection of components

The integrated system allows the AUV to autonomously navigate competition courses while detecting and interacting with various underwater elements. Testing and validation were performed extensively in both simulated and real-world environments.


<div style="text-align: center;">
  <img src="/STA.github.io/images/image_2_1.png" width="500">
</div>


<div style="text-align: center;">
  <video controls width="500">
    <source src="/STA.github.io/images/video_2_1.mp4" type="video/mp4">
  </video>
</div>
