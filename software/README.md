# Software

## 📌 Overview

This folder contains the software and programming documentation used for the **IoT-Enabled Intelligent Sewer Monitoring and Flood Risk Early-Warning System**.

The software controls the ESP8266, processes sensor readings, determines drainage conditions, and sends monitoring data to the web dashboard.

## 💻 Software Used

- Arduino IDE
- ESP8266 programming environment
- Wi-Fi communication
- Web-based IoT monitoring dashboard

## ⚙️ Software Functions

The program performs the following functions:

1. Reads water-level information from the ultrasonic sensor.
2. Reads water-flow information from the flow sensor.
3. Detects rainfall using the rain sensor.
4. Processes the sensor readings using predefined conditions.
5. Determines the drainage status.
6. Displays information on the 16×2 I2C LCD.
7. Sends data through ESP8266 Wi-Fi.
8. Updates the web dashboard.
9. Displays warning information for critical conditions.
10. Stores monitoring data for CSV download.

## 🚦 Drainage Status Logic

```text
Water Level ≥ 90%
        ↓
    OVERFLOW

Rain = YES
AND Water Level ≥ 70%
        ↓
   RAIN OVERFLOW

Water Flow = NO
AND Water Level ≥ 65%
        ↓
     BLOCKAGE

Water Flow = NO
        ↓
      NO FLOW

Water Flow = YES
AND Water Level < 65%
        ↓
    NORMAL FLOW
