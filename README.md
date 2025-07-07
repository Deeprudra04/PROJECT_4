# 🚁 Warehouse Drone – e-Yantra Robotics Competition 2024

This project was developed as part of the **e-Yantra Robotics Competition (eYRC) 2024**, organized by IIT Bombay under the theme **"Warehouse Drone"**. The goal was to create a reliable autonomous drone system capable of mapping warehouse environments and identifying packages using computer vision and ROS2.

> 🗓️ Project Duration: August 2024 – November 2024  
> 🧠 Domain: Drone Autonomy, Computer Vision, Robotics, ROS2

---

## 📌 Problem Statement

Design and implement a drone-based solution that:
- Navigates autonomously within a simulated warehouse environment
- Maps the layout using an overhead camera
- Detects and identifies packages accurately
- Communicates efficiently and reliably with a ground control system

---

## 🔧 Features Implemented

### 🧠 Autonomous Navigation
- Developed a drone navigation algorithm with integrated **path planning** logic
- Used overhead camera data to map and traverse the warehouse grid

### 📡 Communication Layer
- Implemented **CRSF (Crossfire) protocol** on **ROS2 Humble** to enable robust UAV communication and telemetry

### 🎛️ PID Control Interface
- Built a custom **PID tuning GUI** for real-time quadcopter control
- GUI includes:
  - Button-based control for discrete steps
  - Slider-based interface for continuous tuning

### 🎯 Precision Localization
- Integrated **WhyCon**: a low-cost, vision-based marker tracking system
- Achieved **millimeter-level precision** in real-time using standard webcams

---

## 🖥️ Tech Stack

| Category         | Tools / Technologies                      |
|------------------|-------------------------------------------|
| OS & Platform    | Ubuntu 22.04, Gazebo, ROS2 Humble         |
| Language         | Python, C++                               |
| Communication    | MAVLink, CRSF Protocol                    |
| Vision & Mapping | OpenCV, WhyCon, Camera Calibration Tools  |
| GUI              | Python Tkinter, rqt                       |
| Hardware (Simulated) | PX4, Quadcopter model, Overhead Camera     |

---

## 📷 Screenshots (Optional)

> _You can include visuals of:_
- The warehouse environment
- Your drone in Gazebo
- GUI interface for PID tuning
- Marker-based localization with WhyCon

---

## 📁 Folder Structure (Example)

