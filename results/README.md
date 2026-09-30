# Results

## 📌 Overview

This folder contains the testing and performance results of the **IoT-Enabled Intelligent Sewer Monitoring and Flood Risk Early-Warning System**.

The prototype was tested under different water-level, flow, rainfall, blockage, overflow, and dashboard monitoring conditions.

## 🧪 Tests Conducted

- Water Level Detection Test
- Water Flow Detection Test
- Rain Detection Test
- Blockage Detection Test
- Overflow Detection Test
- Dashboard and Live Monitoring Test
- Overall Performance Evaluation

## 📊 Main Results

### Water Level Detection

| Trial | Actual Level | Measured Level | Result |
|---|---:|---:|---|
| 1 | 3 | 3.2 | Pass |
| 2 | 5 | 5.1 | Pass |
| 3 | 7 | 7.2 | Pass |
| 4 | 9 | 9.1 | Pass |
| 5 | 11 | 10.9 | Pass |

### Water Flow Detection

| Trial | Flow Condition | Detected Status | Result |
|---|---|---|---|
| 1 | Normal Flow | Normal Flow | Pass |
| 2 | Normal Flow | Normal Flow | Pass |
| 3 | Reduced Flow | Low Flow | Pass |
| 4 | No Flow | No Flow | Pass |
| 5 | Normal Flow | Normal Flow | Pass |

### Rain Detection

| Trial | Test Condition | Detection | Result |
|---|---|---|---|
| 1 | Dry | No Rain | Pass |
| 2 | Light Rain | Rain Detected | Pass |
| 3 | Moderate Rain | Rain Detected | Pass |
| 4 | Heavy Rain | Rain Detected | Pass |
| 5 | Dry | No Rain | Pass |

### Blockage Detection

| Trial | Condition | Flow Status | Warning |
|---|---|---|---|
| 1 | Normal | Normal Flow | No Warning |
| 2 | Partial Blockage | Low Flow | Blockage Warning |
| 3 | Partial Blockage | Low Flow | Blockage Warning |
| 4 | Complete Blockage | No Flow | Blockage Warning |
| 5 | Normal | Normal Flow | No Warning |

### Overflow Detection

| Trial | Water Level Condition | System Status | Result |
|---|---|---|---|
| 1 | Low | Normal | Pass |
| 2 | Medium | Normal | Pass |
| 3 | High | Warning | Pass |
| 4 | Critical | Overflow Warning | Pass |
| 5 | Critical | Overflow Warning | Pass |

## 🌐 Dashboard Test

| Parameter | Monitoring Status | Result |
|---|---|---|
| Water Level | Live | Pass |
| Water Flow | Live | Pass |
| Rain Detection | Live | Pass |
| Blockage Status | Live | Pass |
| Overflow Status | Live | Pass |
| Warning Information | Displayed | Pass |
| CSV Data Download | Available | Pass |

## 📈 Overall Performance

The testing demonstrated that the prototype could monitor:

- Water level
- Water flow
- Rainfall
- Possible blockage
- No-flow conditions
- Overflow conditions

The system displayed the monitored information through the **16×2 LCD and web dashboard**. Live graphs, warning information, and CSV data recording were also demonstrated.

## 📌 Conclusion

The prototype successfully demonstrated a low-cost IoT-based approach for continuous drainage monitoring and early identification of abnormal conditions such as blockage and overflow.
