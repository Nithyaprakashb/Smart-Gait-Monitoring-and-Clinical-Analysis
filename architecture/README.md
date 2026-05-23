# System Architecture and Operational Workflow

The Smart Gait Monitoring and Clinical Analysis System is designed as a wearable biomedical IoT platform that combines embedded sensing, real-time wireless communication, mobile visualization, and clinical gait interpretation into a compact and portable healthcare-oriented solution.

The architecture focuses on achieving reliable plantar pressure acquisition, efficient embedded processing, low-power BLE communication, and clinically meaningful gait analysis through a user-friendly Flutter-based mobile application.

Unlike traditional gait assessment systems that depend on laboratory equipment and expensive motion-capture platforms, this system provides a lightweight and wearable alternative capable of operating in real-world rehabilitation and monitoring environments.

---

# Core Architecture Overview

The complete system consists of four major operational layers:

## 1. Wearable Sensor Layer
The sensing layer consists of smart insoles integrated with Force Sensitive Resistor (FSR) sensors positioned at critical plantar pressure regions including:
- Toe region
- Heel region
- Mid-foot pressure zones

These sensors continuously detect pressure distribution variations generated during standing, walking, rehabilitation exercises, and gait transitions.

The wearable architecture is designed to:
- Maintain flexibility and comfort
- Minimize motion restrictions
- Support continuous monitoring
- Ensure stable sensor positioning during movement

---

## 2. Embedded Processing Layer

The embedded processing layer is powered by the ESP32-WROOM microcontroller which acts as the central computational and communication unit of the system.

### Responsibilities of ESP32:
- Real-time analog signal acquisition
- Sensor calibration
- Pressure normalization
- BLE communication handling
- Dual insole synchronization
- Noise filtering and stabilization
- Data packet management

The ESP32 continuously receives analog outputs from the FSR sensors through ADC channels and converts them into normalized digital pressure values for further processing.

The embedded firmware architecture is optimized for:
- Low power consumption
- Stable wireless communication
- Real-time responsiveness
- Portable wearable operation

---

## 3. Wireless Communication Layer

Bluetooth Low Energy (BLE) communication is used to establish wireless data transfer between the smart insoles and the Flutter mobile application.

### BLE Features:
- Low-latency communication
- Energy-efficient operation
- Real-time streaming
- Independent left-right insole communication
- Reliable packet transmission

The BLE layer enables seamless synchronization between wearable hardware and mobile visualization without requiring external infrastructure or wired communication.

---

## 4. Mobile Application and Clinical Analysis Layer

The Flutter-based mobile application serves as the primary visualization and interaction interface for the user.

The application receives live plantar pressure data and converts it into clinically interpretable visual outputs.

### Mobile Application Capabilities:
- Real-time pressure visualization
- Left-right gait symmetry monitoring
- Toe and heel pressure evaluation
- Rehabilitation progress tracking
- Fall-risk indication
- Baseline calibration
- Session monitoring
- PDF session export

The interface is designed using a clinical dark-theme dashboard to improve readability, user focus, and professional medical-style visualization.

---

# Operational Workflow

The system workflow follows a continuous real-time monitoring pipeline.

## Step 1 — System Initialization
When powered ON, the ESP32 initializes:
- ADC channels
- BLE communication services
- Sensor calibration modules
- Wireless synchronization routines

The mobile application scans and connects to the wearable smart insoles through BLE communication.

---

## Step 2 — Baseline Calibration
The user performs a baseline standing posture while the system records reference plantar pressure values.

This calibration process:
- Improves pressure normalization
- Enhances sensor stability
- Reduces false gait interpretations
- Adapts the system to individual users

---

## Step 3 — Real-Time Pressure Acquisition
FSR sensors continuously capture pressure variations generated during walking or standing activities.

Pressure changes from:
- Heel strike
- Mid-foot transition
- Toe-off propulsion

are dynamically monitored and processed.

---

## Step 4 — Embedded Signal Processing
The ESP32 performs:
- Analog-to-digital conversion
- Pressure scaling
- Data normalization
- Noise reduction
- Signal stabilization

The processed values are prepared for wireless streaming.

---

## Step 5 — BLE Data Transmission
Normalized pressure data is transmitted wirelessly through BLE notify characteristics.

The communication architecture supports:
- Stable continuous streaming
- Low-power operation
- Real-time synchronization
- Minimal transmission latency

---

## Step 6 — Mobile Visualization and Clinical Interpretation
The Flutter application receives the incoming data streams and visualizes:
- Plantar pressure distribution
- Left-right asymmetry
- Toe and heel loading
- Stability indicators
- Rehabilitation progress

The application further applies rule-based clinical logic to identify potential gait abnormalities and rehabilitation conditions.

---

## Step 7 — Session Reporting and Monitoring
The application supports PDF session export functionality for:
- Rehabilitation documentation
- Clinical review
- Follow-up tracking
- Academic evaluation

This enables the system to function as both a wearable monitoring tool and a portable rehabilitation support platform.

---

# Process Workflow Diagram

The following workflow diagram illustrates the complete operational pipeline of the Smart Gait Monitoring System from wearable sensor initialization to clinical gait interpretation and session reporting.

![Process Workflow](architecture/process-workflow.png)

---

# Hardware Integration

## Embedded Hardware Components

| Component | Function |
|---|---|
| ESP32-WROOM | Embedded processing and BLE communication |
| FSR Sensors | Plantar pressure sensing |
| Smart Insoles | Wearable sensor platform |
| Li-Po Battery | Portable power supply |
| TP4056 Module | Battery charging and protection |
| MT3608 Converter | Voltage boosting and regulation |

---

# Hardware Design Considerations

The hardware architecture was designed with emphasis on:
- Wearability
- Portability
- Low-power operation
- User comfort
- Real-time responsiveness
- Biomedical safety considerations

Special attention was given to maintaining flexible insole structure while preserving accurate sensor positioning and signal consistency.

---

# Hardware Setup Image

<img width="1153" height="1536" alt="Hardware-Setup" src="https://github.com/user-attachments/assets/ec638272-235e-4ca1-a9f1-5e0791530216" />
