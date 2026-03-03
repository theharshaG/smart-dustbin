# smart-dustbin
# Smart Dustbin using ESP32

## Overview
This project implements a touchless smart dustbin using
an ultrasonic sensor and a servo motor.

When a hand is detected within 15 cm,
the lid opens automatically and closes after a delay.

## Components
- ESP32
- Ultrasonic Sensor (HC-SR04)
- Servo Motor (SG90)
- Jumper Wires

##  Working
1. Ultrasonic sensor measures distance.
2. If distance ≤ 15 cm → lid opens.
3. After 3 seconds → lid closes.

## Concepts Learned
- Ultrasonic distance calculation
- Servo motor control
- Automation logic
- Embedded system design

## Author
Harsha G
