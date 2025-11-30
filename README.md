# Advance_Cruise_Control
``` 
🚗 Lane Detection and Cruise Control System for Autonomous Driving
Senior Design Project 

Department of Electronics and Communication Engineering
```
# Abstract
```
Driving long distances increases fatigue and accident risk. This project presents a real-time Advanced Cruise Control (ACC) with Lane Detection System using Raspberry Pi, ultrasonic sensing, and computer vision.
The system dynamically adjusts speed, detects obstacles, identifies lanes, and simulates safe autonomous driving behavior.
```

# Table of Contents 
```
Introduction

Motivation

Objectives

Literature Survey

Project Planning

Components Specification

Methodology

Results

Applications

Advantages

Future Work

Conclusion
```

# Introduction
```
Modern vehicles require continuous acceleration, braking, and lane maintenance. This project integrates:

Adaptive Cruise Control

Lane Detection

Obstacle Detection

DC motor speed simulation

using a Raspberry Pi and sensors to create an entry-level autonomous driving prototype.
```
# 🎯 Objectives
```
Develop ACC system that adjusts speed automatically

Integrate Raspberry Pi, camera, ultrasonic sensor & motor

Implement lane detection using OpenCV

Simulate ACC in MATLAB/Simulink

Demonstrate obstacle-based braking and reacceleration
```

# 🔧 Components Specification
```
Raspberry Pi

Quad-core ARM processor

40 GPIO pins

Wi-Fi & Bluetooth

Camera Module

CSI Interface

Used for lane & object detection

Ultrasonic Sensor

HC-SR04

Range: 2–400 cm

Distance measurement

DC Motor + Driver

Used to simulate vehicle acceleration/braking
```

# Methodology 

<img src="https://github.com/Prathameshgunjikar/Advance_Cruise_Control/blob/main/images/block_diagram.png" width="400"/>

# 🧪 Results

![Hardware Implementation](images/hardware.png)

```
ACC simulation validated speed control

Lane detection worked reliably in video tests

Hardware prototype successfully varied motor speed

Smooth deceleration and reacceleration observed

Limitations: lighting, sensor noise, Raspberry Pi processing speed
```

# 🏁 Conclusion
```
This project successfully demonstrates a low-cost, fully functional Lane Detection + Adaptive Cruise Control system using Raspberry Pi, embedded control, and computer vision.

It provides a foundation for future autonomous vehicle research and advanced driver-assistance systems.
```
