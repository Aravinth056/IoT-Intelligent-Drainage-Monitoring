# Hardware

## 📌 Overview

This folder contains the hardware components used to develop the **IoT-Enabled Intelligent Sewer Monitoring and Flood Risk Early-Warning System**.

The hardware collects drainage information and sends it to the ESP8266 NodeMCU for processing and monitoring.

## 🔧 Main Components

| No. | Component | Purpose |
|---|---|---|
| 1 | ESP8266 NodeMCU | Main controller and Wi-Fi communication |
| 2 | HC-SR04 Ultrasonic Sensor | Water-level measurement |
| 3 | Water Flow Sensor | Flow-rate measurement |
| 4 | Digital Water Flow Detector | Detects water-flow / no-flow condition |
| 5 | Rain Sensor | Rainfall detection |
| 6 | 16×2 I2C LCD | Displays sensor readings and system status |
| 7 | Water Level Sensor Module | Additional water-level information |
| 8 | 5V DC Power Supply | Supplies power to the system |
| 9 | Protective Sensor Enclosure | Protects electronic components from water |
| 10 | Drainage Prototype Channel | Provides the test environment |

## ⚙️ Hardware Arrangement

```text
HC-SR04 ─────────────┐
                     │
Water Flow Sensor ───┤
                     │
Rain Sensor ─────────┤
                     ↓
              ESP8266 NodeMCU
                     │
          ┌──────────┴──────────┐
          ↓                     ↓
      16×2 LCD            Wi-Fi Dashboard
