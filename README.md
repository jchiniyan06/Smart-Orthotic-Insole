# Smart Orthotic Insole

An ESP32-based smart orthotic insole designed to monitor foot pressure and collect real-time data for analysis.

## 📌 Project Overview

The Smart Orthotic Insole is a hardware prototype designed to measure pressure distribution across different regions of the foot using pressure sensors and an ESP32 microcontroller.

The collected sensor data can be used for monitoring and further analysis of foot pressure and gait patterns.

## 🎯 Objectives

- Measure foot pressure at multiple locations
- Collect sensor data using ESP32
- Monitor pressure distribution
- Develop a low-cost wearable prototype
- Provide a platform for future gait analysis

## 🔧 Hardware Components

- ESP32
- FSR pressure sensors
- MPU6050
- Resistors
- Orthotic insoles
- Connecting wires
- Prototype board

## ⚙️ Working Principle

Pressure sensors are positioned at selected locations on the insole.

When pressure is applied while standing or walking, the sensor resistance changes. The ESP32 reads these sensor signals and processes the corresponding values.

The collected data can then be used to analyze pressure distribution across the foot.

## 🧪 Prototype

The current prototype integrates the insoles, sensors, ESP32 and supporting electronic components.

![Smart Orthotic Insole Prototype](prototype%20image.jpeg)

## 📁 Project Structure

```text
Smart-Orthotic-Insole/
│
├── README.md
├── prototype image.jpeg
├── Code/
├── Circuit/
├── Hardware/
└── Documentation/
