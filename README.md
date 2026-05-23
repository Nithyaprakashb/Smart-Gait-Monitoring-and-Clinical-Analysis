# Smart Gait Monitoring and Clinical Analysis System

## Overview
The Smart Gait Monitoring and Clinical Analysis System is a wearable biomedical IoT solution developed for real-time plantar pressure monitoring, gait pattern evaluation, and rehabilitation support. The system utilizes smart insoles embedded with Force Sensitive Resistor (FSR) sensors to capture foot pressure distribution during standing and walking activities.

The collected sensor data is processed using an ESP32 microcontroller and transmitted wirelessly through Bluetooth Low Energy (BLE) communication to a Flutter-based mobile application. The mobile application visualizes plantar pressure patterns, gait asymmetry, balance variations, and rehabilitation progress through an intuitive clinical-style user interface.

This project is designed to support:
- Gait screening
- Rehabilitation monitoring
- Biomechanical analysis
- Fall-risk indication
- Lower limb assessment
- Portable wearable healthcare applications

The system focuses on providing a low-cost, portable, and clinically inspired gait monitoring platform suitable for academic research, embedded system development, biomedical applications, and wearable healthcare innovation.

---

# Objectives
- Develop a wearable plantar pressure monitoring system
- Analyze gait symmetry and foot pressure distribution
- Provide real-time wireless monitoring using BLE
- Create a mobile application for visualization and analysis
- Support rehabilitation and gait assessment applications
- Design a lightweight and portable biomedical device

---

# Key Features
- Real-time plantar pressure sensing
- Dual smart insole architecture
- BLE-based wireless communication
- ESP32-based embedded processing
- Flutter mobile application interface
- Clinical-style gait visualization
- Baseline calibration support
- Portable wearable design
- Pressure distribution monitoring
- Toe and heel pressure analysis
- User-friendly dashboard
- Low-power operation
- Rehabilitation support functionality

---

# System Workflow

1. Force Sensitive Resistors (FSR) placed inside the insoles detect plantar pressure variations.

2. The ESP32 microcontroller acquires analog sensor signals through ADC channels.

3. Sensor readings are processed and normalized for pressure evaluation.

4. Processed data is transmitted wirelessly using Bluetooth Low Energy (BLE).

5. The Flutter mobile application receives live sensor data.

6. The application visualizes:
   - Left-right pressure symmetry
   - Toe and heel pressure
   - Pressure distribution
   - Gait balance indicators

7. Clinical screening logic analyzes gait conditions and generates insights.

---

# Hardware Components

| Component | Purpose |
|---|---|
| ESP32-WROOM | Main microcontroller and BLE communication |
| FSR Sensors | Plantar pressure sensing |
| Smart Insoles | Sensor mounting platform |
| Li-Po Battery | Portable power supply |
| TP4056 Module | Battery charging and protection |
| MT3608 Boost Converter | Voltage regulation |
| BLE Communication | Wireless data transmission |
| Wiring and Connectors | Hardware integration |

---

# Software and Technologies Used

## Embedded Systems
- ESP32 Firmware Development
- Analog Signal Processing
- Sensor Calibration
- BLE Communication

## Mobile Application
- Flutter Framework
- Real-time Data Visualization
- Mobile UI/UX Design
- Bluetooth Integration

## Biomedical and IoT Technologies
- Biomedical Signal Monitoring
- Plantar Pressure Analysis
- Wearable Healthcare Technology
- IoT System Architecture
- Rehabilitation Monitoring

---

# System Architecture

The overall architecture consists of five major layers:

## 1. Sensor Layer
FSR sensors embedded inside smart insoles measure pressure applied at toe and heel regions.

## 2. Embedded Processing Layer
ESP32 processes sensor data, performs normalization, and manages BLE communication.

## 3. Wireless Communication Layer
BLE protocol enables low-power real-time wireless transmission.

## 4. Mobile Application Layer
Flutter application visualizes gait information using a clinical dashboard interface.

## 5. Analysis and Reporting Layer
The system evaluates gait patterns, symmetry, and rehabilitation indicators.

---

# Clinical and Biomedical Applications
- Rehabilitation monitoring
- Physiotherapy assistance
- Post-stroke gait analysis
- Fall-risk observation
- Sports biomechanics
- Elderly mobility monitoring
- Wearable healthcare systems
- Academic biomedical research

---

# Safety and Design Considerations
- Low-voltage wearable architecture
- Skin-friendly insole materials
- Portable and lightweight design
- Battery protection circuitry
- BLE low-power communication
- Comfortable wearable structure
- Sensor isolation and protection

---

# Mobile Application Features
- Real-time pressure monitoring
- Left-right gait comparison
- Clinical analysis dashboard
- Pressure visualization
- BLE connectivity management
- Baseline calibration
- Session monitoring
- User-friendly dark theme interface

---

# Application Screenshots
(Add screenshots here)

Example:
```md
![Home Screen](screenshots/home-screen.jpg)
![Clinical Dashboard](screenshots/dashboard.jpg)
```

---

# Architecture Diagrams
(Add architecture and workflow diagrams here)

Example:
```md
![System Architecture](architecture/system-architecture.png)
![BLE Workflow](architecture/ble-flow.png)
```

---

# Hardware Setup
(Add hardware setup images here)

Example:
```md
![ESP32 Setup](hardware/esp32-setup.jpg)
![FSR Sensors](hardware/fsr-sensors.jpg)
```

---

# Future Enhancements
- AI-based gait prediction
- Machine learning integration
- Cloud-based health monitoring
- Advanced biomechanical analytics
- Multi-user patient tracking
- Real-time rehabilitation feedback
- Medical report automation
- Edge AI implementation on ESP32

---

# Repository Structure

```bash
SMART-GAIT/
│
├── README.md
├── screenshots/
├── hardware/
├── architecture/
├── docs/
└── assets/
```

---

# Disclaimer
This repository is intended for showcasing project architecture, hardware integration, workflow design, documentation, and user interface previews only.

Source code, firmware, proprietary algorithms, and implementation details are intentionally excluded to protect client confidentiality and intellectual property.

---

# Author
Developed as a biomedical embedded IoT project focused on wearable gait monitoring and clinical analysis using ESP32, BLE communication, and Flutter-based visualization systems.

# Contact

For collaborations, academic projects, biomedical systems, embedded hardware solutions, electrical projects, IoT systems, AI/ML integration, and wearable healthcare innovations:

📧 Email: nithyaprakashedu@gmail.com

Areas of Interest:
- Biomedical Engineering Projects
- Embedded Systems Development
- ESP32 and IoT Solutions
- Electrical and Electronics Hardware Projects
- AI and Machine Learning Integration
- Flutter Application Development
- Wearable Healthcare Systems
- Sensor-Based Automation Systems
- Rehabilitation and Clinical Monitoring Solutions
