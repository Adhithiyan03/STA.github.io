---
title: "Visual Inertial Odometry with Multi-Constraint EKF and Unsupervised Learning Approaches"
excerpt: "Use of IMU and RGB Camera for optimal estimation of relative postion of AV <br/><img src='/STA.github.io/images/image_6_0.jpg'>"  
collection: portfolio
---

In this report, network architectures and loss functions are proposed that is used to estimate odometry/ relative pose between scenes using IMU (Inertial measurement unit) readings and camera frames. The process used to generate synthetic data for training and testing of these models is discussed along with recorded results

Multi-Constraint Kalman Filter - means of solving the VIO (Visual-Inertial Odometry) problem
  Satisfactory results - RMSE ATE between ground truth and estimates
  heavy dependency on feature detection and tracking

Can we use deep feature tracking? Pretty straightforward for visual but for IMU data?

Scarcity in deep learning methods in literature for VIO
We propose networks trained on synthetic data to estimate odometry given the visual and inertial data



<div style="text-align: center;">
  <video controls width="500">
    <source src="/STA.github.io/images/image_6_1.jpg" width="500">
  </video>
</div>

<div style="text-align: center;">
  <video controls width="500">
    <source src="/STA.github.io/images/imag_6_2.png" width="500">
  </video>
</div>

<div style="text-align: center;">
  <video controls width="500">
    <source src="/STA.github.io/images/imag_6_3.png" width="500">
  </video>
</div>
