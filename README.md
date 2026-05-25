# Multi-Sensor Perception System

A Raspberry Pi-based multi-sensor perception system designed for low-visibility and partially occluded environments.

## Project Goal

Develop a modular perception platform capable of detecting:

- Objects
- Motion
- Human presence
- Environmental changes

using multiple sensing technologies combined through sensor fusion.

---

# Sensors

## VL53L0X ToF LiDAR
Used for:

- Distance measurement
- Geometry sensing
- Obstacle detection

## Ultrasonic Sensors
Used for:

- Close-range detection
- Redundant distance verification

## RCWL-0516 Radar
Used for:

- Motion detection
- Presence sensing
- Partial occlusion detection

## MLX90640 Thermal Camera
Used for:

- Thermal imaging
- Heat signatures
- Human detection

---

# Core Concepts

- Sensor fusion
- Low-visibility perception
- Multi-modal sensing
- Edge computing
- Environmental awareness
- Occluded object detection

---

# Hardware

- Raspberry Pi 4
- VL53L0X ToF sensors
- Ultrasonic sensors
- RCWL-0516 radar sensors
- MLX90640 thermal camera
- Breadboards
- Logic level converters
- Buzzers
- Amplifiers
- Jumper wires

---

# Planned Features

- Real-time sensor monitoring
- Confidence scoring
- Multi-sensor fusion engine
- Human presence detection
- Motion tracking
- Alert system
- Environmental mapping
- Logging and diagnostics

---

# Project Structure

```text
MultiSensor-Perception-System/
├── docs/
├── simulations/
├── src/
│   ├── fusion/
│   ├── sensors/
│   └── main.py
├── tests/
├── .gitignore
├── README.md
└── requirements.txt