# EE615-Sensor Fusion for Orientation Estimation using Extended Kalman Filter

## 📌 Overview
This project implements a **quaternion-based Extended Kalman Filter (EKF)** for fusing gyroscope and accelerometer data to achieve accurate 3D orientation estimation. The system was validated using an **MPU6050 IMU** and real-time visualization in MATLAB.

## ⚡ Objectives
- Fuse gyroscope and accelerometer data to compensate drift and noise.
- Implement quaternion-based EKF for robust 3D orientation tracking.
- Validate performance against MATLAB’s built-in `imufilter`.

## 🛠️ Methodology
- **Sensor Data Acquisition:** Real-time IMU data captured via Arduino from MPU6050.
- **EKF Implementation:** Quaternion-based state estimation pipeline coded in MATLAB.
- **Comparison:** Output compared with MATLAB’s `imufilter` for benchmarking.
- **Visualization:** 3D orientation tracking displayed live in MATLAB.

## 📊 Results
- EKF provided **drift-compensated orientation** with stable 3D tracking.  
- Outperformed raw sensor fusion by **reducing noise and cumulative drift**.  
- Accuracy validated against MATLAB’s `imufilter`, showing **comparable results with improved stability**.
- The results, plots , code are attached in the report which has been uploaded in the repository.
