# Obstacle Avoiding Robot Car 🚗🤖

An Arduino-based obstacle avoiding robot car designed to autonomously detect obstacles using an ultrasonic sensor and navigate by controlling DC motors through a motor driver.

**Project Status: ✅ Functional & Complete (90%)**  
This project is now **actively working and functional**!  
The robot successfully detects obstacles using an ultrasonic sensor and autonomously navigates by controlling motors through the motor driver module. Minor optimizations and edge-case handling remain for full 100% completion.

---

## Features ✨
- ✅ Autonomous obstacle detection using ultrasonic sensor (HC-SR04)
- ✅ Motor control via motor driver module (L298N)
- ✅ Directional decision making (left / right turn)
- ✅ Modular and extensible Arduino code
- 🔄 Performance optimization (in progress)

---

## Components Used
- Arduino Uno (Clone)
- Ultrasonic Sensor (HC-SR04)
- Motor Driver Module (L298N)
- DC Motors with Robot Chassis
- External Battery Supply
- Jumper Wires

---

## Working Principle
1. Ultrasonic sensor measures distance ahead.
2. Arduino processes distance data and applies threshold logic.
3. Based on detected distance:
   - Robot moves forward when path is clear
   - Stops and changes direction (left/right) when obstacle is detected
4. Motors are driven using control signals from the motor driver (PWM speed control).

---

## Project Achievements 🎯
- ✅ All hardware connections verified and working correctly
- ✅ Motor control fully functional
- ✅ Obstacle detection logic implemented and tested
- ✅ Autonomous navigation successfully demonstrated
- ✅ Code modular and extensible

---

## Ongoing Optimization
- Fine-tuning sensor sensitivity thresholds
- Optimizing turning angles and speed control
- Testing edge cases and obstacle scenarios
- Performance improvements for dynamic environments

---

## How to Use
1. Upload the Arduino sketch to your Arduino Uno
2. Ensure all hardware connections match the wiring diagram
3. Power on the robot and place it on the ground
4. The robot will autonomously detect obstacles and navigate around them

---

**Last Updated:** March 27, 2026  
**Completion Status:** 90% - Functional and working as intended ✅
