# Working Principle

## 📌 Overview

The **IoT-Enabled Intelligent Sewer Monitoring and Flood Risk Early-Warning System** continuously monitors drainage conditions using sensors connected to an **ESP8266 NodeMCU**.

The system monitors:

- Water level
- Water flow
- Rainfall
- Blockage conditions
- Overflow conditions

The collected information is transmitted through Wi-Fi to a web-based monitoring dashboard.

---

## ⚙️ Working Process

The system works in the following sequence:

```text
Water Level Sensor
        ↓
Water Flow Sensor
        ↓
Rain Sensor
        ↓
ESP8266 NodeMCU
        ↓
Data Processing
        ↓
Wi-Fi Communication
        ↓
Web Dashboard
        ↓
Warning / Status Information
