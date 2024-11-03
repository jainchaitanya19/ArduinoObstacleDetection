# Autonomous Drone Control System

This project implements an autonomous drone control system using an Arduino platform. It integrates ultrasonic sensors for obstacle detection, and LED indicators for status signaling. Although the initial design includes servo motors for controlling roll, pitch, and throttle, this version does not currently utilize them in the control logic. The system is designed to navigate autonomously while avoiding obstacles in real-time.

## Features
- Ultrasonic sensors for obstacle detection in multiple directions
- Intended integration of servo motors for movement control (not used in the current implementation)
- LED indicators to signal system status
- Real-time distance measurements for autonomous navigation

## Hardware Requirements
- Arduino board (e.g., Arduino Uno)
- Ultrasonic distance sensors (e.g., HC-SR04)
- WS2812 LED strip (or similar)
- Connecting wires and breadboard

## Software Requirements
- Arduino IDE
- NewPing library
- FastLED library

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AutonomousDroneControlSystem.git

