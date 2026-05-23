# Smart Gait Monitoring and Clinical Analysis System

## Overview

The Smart Gait Monitoring and Clinical Analysis System is a wearable biomedical IoT platform developed for real-time plantar pressure monitoring, gait symmetry evaluation, rehabilitation tracking, and wireless biomechanical analysis.

The system integrates smart insoles embedded with Force Sensitive Resistor (FSR) sensors, ESP32-based embedded processing, Bluetooth Low Energy (BLE) communication, and a Flutter-based mobile application for real-time visualization and clinical interpretation.

The project was designed as a portable and low-cost alternative to traditional gait laboratory systems, enabling wearable healthcare monitoring and rehabilitation-focused analysis in real-world environments.

The system focuses on:
- Real-time gait monitoring
- Plantar pressure analysis
- Wearable biomedical sensing
- Rehabilitation support
- Clinical visualization
- Portable embedded healthcare systems

---

# Objectives

## Primary Objectives
- Develop a wearable smart gait monitoring platform
- Monitor plantar pressure distribution in real-time
- Enable BLE-based wireless communication
- Visualize gait data through a Flutter mobile application
- Analyze gait symmetry and pressure imbalance

## Secondary Objectives
- Support rehabilitation monitoring
- Improve mobility assessment portability
- Create a low-cost wearable healthcare solution
- Provide clinically inspired visualization
- Enable scalable biomedical IoT integration

---

# Key Features

- Real-time plantar pressure sensing
- BLE wireless communication
- Dual smart insole architecture
- Flutter-based mobile application
- Clinical gait analysis dashboard
- Left-right gait symmetry evaluation
- Toe and heel pressure monitoring
- Rehabilitation tracking support
- Portable wearable architecture
- Low-power embedded operation
- Session monitoring and PDF export
- Baseline calibration support

---

# System Architecture and Workflow

The Smart Gait Monitoring System follows a wearable embedded IoT architecture designed for continuous plantar pressure sensing, real-time wireless communication, mobile visualization, and rehabilitation-oriented gait analysis.

The architecture combines wearable sensors, embedded processing, BLE communication, and mobile analytics into a compact healthcare-oriented platform.

---

## 1. Wearable Sensor Layer

The sensing layer consists of smart insoles integrated with Force Sensitive Resistor (FSR) sensors positioned at critical plantar pressure regions including:
- Toe region
- Heel region
- Mid-foot region

The sensors continuously capture pressure variations generated during walking, standing, and rehabilitation activities.

The wearable design prioritizes:
- Flexibility
- User comfort
- Stable sensor placement
- Continuous monitoring capability

---

## 2. Embedded Processing Layer

The embedded architecture is powered by the ESP32-WROOM microcontroller which performs:
- Analog signal acquisition
- Sensor calibration
- Pressure normalization
- BLE communication management
- Signal stabilization
- Data synchronization

The ESP32 continuously processes analog pressure signals from the FSR sensors through ADC channels and converts them into normalized digital pressure data.

The embedded firmware is optimized for:
- Low power consumption
- Stable real-time communication
- Portable operation
- Wearable integration

---

## 3. Wireless Communication Layer

Bluetooth Low Energy (BLE) is used for wireless data transmission between the wearable hardware and the mobile application.

### BLE Communication Features
- Low-latency transmission
- Real-time streaming
- Energy-efficient operation
- Reliable wireless synchronization
- Continuous gait monitoring support

The BLE architecture enables seamless communication without requiring external wired infrastructure.

---

## 4. Mobile Application and Clinical Analysis Layer

The Flutter-based mobile application acts as the visualization and clinical interaction interface of the system.

The application receives live pressure data and converts it into clinically interpretable visual outputs.

### Application Features
- Real-time plantar pressure visualization
- Left-right gait comparison
- Toe and heel pressure analysis
- Rehabilitation progress tracking
- Clinical gait indicators
- Session export functionality
- BLE connectivity management
- Baseline calibration

The user interface follows a clinical dark-theme dashboard design to improve readability and provide a professional biomedical visualization experience.

---

# Operational Workflow

## Step 1 — System Initialization
The ESP32 initializes:
- ADC channels
- BLE services
- Calibration modules
- Wireless synchronization routines

The mobile application establishes BLE connectivity with the smart insoles.

---

## Step 2 — Baseline Calibration
The system records baseline plantar pressure values to improve sensor accuracy and reduce false gait interpretations.

---

## Step 3 — Real-Time Pressure Acquisition
FSR sensors continuously measure:
- Heel strike pressure
- Mid-foot transition pressure
- Toe-off propulsion force

during standing and walking activities.

---

## Step 4 — Embedded Signal Processing
The ESP32 performs:
- Analog-to-digital conversion
- Signal normalization
- Pressure scaling
- Noise reduction
- Data stabilization

---

## Step 5 — BLE Data Transmission
Processed pressure data is transmitted wirelessly to the Flutter mobile application using BLE communication.

---

## Step 6 — Mobile Visualization and Clinical Analysis
The mobile application visualizes:
- Pressure distribution
- Gait symmetry
- Toe and heel loading
- Stability indicators
- Rehabilitation progress

The system further applies rule-based clinical analysis to identify gait abnormalities and rehabilitation conditions.

---

## Step 7 — Session Reporting
The application supports PDF session export for:
- Rehabilitation documentation
- Clinical review
- Follow-up analysis
- Academic evaluation

---

# Process Workflow Diagram

The following workflow diagram illustrates the complete operational pipeline of the Smart Gait Monitoring System.

<img width="1024" height="1536" alt="workflow" src="https://github.com/user-attachments/assets/60e611db-bf95-425d-9db1-f3912f654e6e" />


---

# Application Screenshots

## Smart Gait Dashboard

The dashboard visualizes real-time plantar pressure distribution for both left and right feet using wearable sensing technology.

### Features Displayed
- Foot pressure visualization
- BLE connectivity status
- Real-time pressure monitoring
- Session export support
- Clinical dashboard interface
- Calibration functionality

<img width="718" height="1600" alt="dashboard-screen" src="https://github.com/user-attachments/assets/5fdc9ca5-f059-4776-ad72-ac4591739256" />

---

## Clinical Analysis Interface

The clinical analysis module evaluates gait abnormalities, rehabilitation progress, lower-limb imbalance, and fall-risk indicators using plantar pressure data.

### Clinical Insights
- Post-stroke gait analysis
- Lower-limb discrepancy monitoring
- Rehabilitation assessment
- Fall-risk indication
- Pressure asymmetry evaluation

<img width="704" height="1600" alt="clinical analysis" src="https://github.com/user-attachments/assets/ebf11df6-0f01-4f13-825b-9559b2129293" />

---

# Hardware Components

| Component | Function |
|---|---|
| ESP32-WROOM | Embedded processing and BLE communication |
| FSR Sensors | Plantar pressure sensing |
| Smart Insoles | Wearable sensor platform |
| Li-Po Battery | Portable power supply |
| TP4056 Module | Battery charging and protection |
| MT3608 Boost Converter | Voltage regulation |

---

# Hardware Integration

The embedded hardware architecture integrates wearable smart insoles, pressure sensors, power management circuitry, and wireless communication modules into a portable biomedical monitoring system.

The hardware setup was designed with emphasis on:
- Wearability
- User comfort
- Low-power operation
- Continuous monitoring
- Stable wireless communication
- Portable biomedical sensing

<img width="609" height="1536" alt="fsr-sensors" src="https://github.com/user-attachments/assets/48257b31-8a02-4040-95eb-006cfc9cc0cf" />

---

# Technologies and Skills Used

## Embedded Systems
- ESP32 Development
- ADC Signal Acquisition
- BLE Communication
- Embedded Firmware Design
- Sensor Calibration

## Mobile Technologies
- Flutter Framework
- Real-Time Mobile Visualization
- Bluetooth Integration
- Mobile UI/UX Design

## Biomedical and IoT Technologies
- Biomedical Signal Processing
- Plantar Pressure Analysis
- Wearable Healthcare Systems
- IoT Architecture
- Rehabilitation Monitoring

---

# Applications

The Smart Gait Monitoring System can be used in:
- Rehabilitation monitoring
- Physiotherapy assistance
- Wearable healthcare systems
- Biomedical research
- Fall-risk analysis
- Sports biomechanics
- Elderly mobility monitoring
- Clinical gait evaluation

---

# Advantages

- Portable wearable architecture
- Real-time wireless monitoring
- Lightweight embedded design
- Low-cost biomedical solution
- User-friendly mobile interface
- Continuous gait observation
- Rehabilitation-focused monitoring
- Scalable IoT healthcare integration

---

# Future Enhancements

Future improvements may include:
- AI/ML-based gait prediction
- Cloud-connected rehabilitation monitoring
- Advanced biomechanics analytics
- Edge AI processing on ESP32
- Multi-patient monitoring support
- Real-time clinician dashboards
- Automated rehabilitation reporting

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

This repository is intended for showcasing:
- System architecture
- Hardware integration
- Workflow design
- Mobile application UI
- Embedded biomedical IoT concepts
- Documentation and presentation materials

Source code, firmware, proprietary algorithms, and confidential implementation details are intentionally excluded to protect client confidentiality and intellectual property.

---

# Contact

For collaborations, biomedical systems, embedded hardware projects, electrical and electronics solutions, IoT systems, wearable healthcare technologies, and AI/ML-integrated applications:

📧 Email: nithyaprakash6666@gmail.com
