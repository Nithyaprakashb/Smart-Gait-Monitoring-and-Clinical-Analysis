# Hardware Components and Integration

The Smart Gait Monitoring System is built using low-power embedded hardware components designed for wearable biomedical sensing, real-time data acquisition, wireless communication, and portable rehabilitation monitoring.

The hardware architecture focuses on portability, reliability, low-latency communication, and continuous plantar pressure sensing during standing and walking activities.

---

# Hardware Overview

The wearable system consists of smart insoles integrated with pressure sensors, an ESP32 microcontroller for embedded processing, battery management circuitry, and BLE communication modules.

The complete hardware setup enables:
- Real-time plantar pressure acquisition
- Wireless gait monitoring
- Portable wearable operation
- Clinical-style rehabilitation tracking
- Low-power embedded processing

---

# Hardware Components

## ESP32-WROOM Development Board

The ESP32-WROOM acts as the central processing and communication unit of the system.

### Functions
- Reads analog sensor data
- Performs signal processing
- Executes pressure normalization
- Handles BLE communication
- Synchronizes left and right insoles

### Features
- Dual-core microcontroller
- Integrated Wi-Fi and BLE
- Low-power operation
- Multiple ADC channels
- Compact embedded architecture

<img width="224" height="224" alt="esp32-wroom" src="https://github.com/user-attachments/assets/316192c4-9257-4ae5-ae88-61bf5991914f" />

---

## Force Sensitive Resistor (FSR) Sensors

FSR sensors are used for plantar pressure sensing inside the smart insoles.

### Sensor Placement
- Toe region
- Mid-foot pressure zones

### Functions
- Detect pressure variations
- Measure toe-off strength
- Monitor heel-strike force
- Analyze gait symmetry

### Advantages
- Thin flexible structure
- Lightweight design
- Fast pressure response
- Suitable for wearable integration

<img width="609" height="1536" alt="fsr-sensors" src="https://github.com/user-attachments/assets/2432b0ae-9b8d-4f9b-8dc8-8b94b8c8fc22" />

---

## Smart Insoles

The smart insoles serve as the wearable substrate for sensor placement and user interaction.

### Functions
- Support embedded sensor mounting
- Maintain user comfort
- Distribute plantar pressure
- Enable wearable gait monitoring

### Design Considerations
- Flexible structure
- Comfortable fit
- Lightweight material
- Continuous wearable operation

<img width="1153" height="1536" alt="flexible-soles" src="https://github.com/user-attachments/assets/7f26e61e-bd43-46bd-b643-b87c7dbcbf34" />

---

## Battery and Power Management System

The system is powered using a rechargeable Li-Po battery combined with charging and voltage regulation modules.

### Components Used
- Li-Po Battery
- TP4056 Charging Module
- MT3608 Boost Converter

### Functions
- Portable power supply
- Safe battery charging
- Stable voltage regulation
- Continuous embedded operation

### Power Design Features
- Low-power wearable architecture
- Battery protection circuitry
- Stable voltage output
- Portable mobile operation
  
<img width="1153" height="1536" alt="bms" src="https://github.com/user-attachments/assets/adc02761-60c4-442b-91df-d9c161059999" />

---

# Hardware Communication Architecture

The hardware components communicate through the ESP32 embedded processing unit.

### Data Flow
1. FSR sensors detect plantar pressure
2. ESP32 acquires analog signals
3. Sensor data is normalized and processed
4. BLE transmits data wirelessly
5. Flutter application visualizes gait metrics

This architecture enables stable real-time gait monitoring and rehabilitation analysis.

---

# Hardware Integration Setup

The complete hardware setup integrates:
- Wearable smart insoles
- Embedded pressure sensors
- ESP32 processing module
- Battery management system
- BLE wireless communication

The setup is designed to maintain portability, flexibility, and continuous wearable monitoring performance.

<img width="1153" height="1536" alt="Hardware-Setup" src="https://github.com/user-attachments/assets/b07b80eb-4d85-4967-afde-034c60db49f0" />

---

# Design Goals

The hardware system was developed with the following objectives:
- Lightweight wearable design
- Real-time sensing capability
- Stable wireless communication
- Low power consumption
- User comfort and portability
- Biomedical monitoring support
- Rehabilitation-focused operation

---

# Safety and Wearability Considerations

Special consideration was given to:
- Sensor insulation
- Comfortable wearable materials
- Low-voltage operation
- Flexible insole construction
- Continuous walking compatibility
- Long-duration wearable usage

The overall hardware architecture aims to balance embedded performance with wearable comfort and clinical usability.
