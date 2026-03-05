# DetachX Car – Modular Smart STEM Car

Team ID: TC26-GF-077
Domain: Electronics

---

## Project Overview

DetachX Car is a modular smart STEM prototype designed to demonstrate the principles of electronics, sensors, embedded systems, and automation through a detachable learning platform.

Unlike traditional robotic kits, this system allows motors, sensors, and control modules to be magnetically attached or detached. This enables students to explore real engineering concepts through physical interaction and system reconfiguration.

---

## Project Images

### Prototype Model

<img width="1210" height="1038" alt="image" src="https://github.com/user-attachments/assets/92ead70a-78a5-40ef-b5f9-628a1604d9aa" />


### System Architecture

<img width="1500" height="784" alt="image" src="https://github.com/user-attachments/assets/5fd415b9-c30f-4267-b437-7cf342ab71ef" />

---

## Key Features

* Modular hardware design with magnetic connectors
* Detachable sensor and motor modules
* ESP32 based control system
* Wireless communication using Bluetooth
* Obstacle detection using ultrasonic sensors
* Line tracking using infrared sensors
* Automatic headlight control using LDR sensor

---

## System Architecture

The DetachX Car follows a modular layered architecture consisting of four primary units.

Control Layer – ESP32 microcontroller responsible for processing and system control.
Sensing Layer – Ultrasonic, IR, and LDR sensors used for environmental detection.
Actuation Layer – Motor units responsible for vehicle movement.
Power Layer – Rechargeable battery supplying power to the system.

All modules are connected using magnetic connectors and copper contact interfaces which allow both mechanical attachment and electrical connectivity.

---

## Hardware Components

* ESP32 Microcontroller
* Ultrasonic Sensor Module
* IR Sensor Module
* LDR Sensor
* Motor Driver and DC Motors
* Rechargeable Battery
* Magnetic Connectors and Copper Contacts
* Modular Chassis

---

## Software Implementation

The system firmware is developed using Embedded C/C++. The software manages Bluetooth communication, sensor data acquisition, motor control through PWM signals, obstacle avoidance logic, and automatic headlight control.

The program structure separates sensing, processing, and actuation functions to maintain a clear and modular software architecture.

---

## Educational Significance

DetachX Car provides a practical platform for learning concepts related to robotics, embedded systems, and mechatronics. The detachable architecture allows students to experiment with system configuration and understand how different hardware components influence system behavior.

---

## Sustainable Development Goals

The project aligns with the following UN Sustainable Development Goals.

SDG 9 – Industry, Innovation and Infrastructure
SDG 11 – Sustainable Cities and Communities
SDG 12 – Responsible Consumption and Production

---

## Conclusion

DetachX Car bridges theoretical knowledge and practical engineering through modular hardware, intelligent sensing, and embedded automation. The system encourages experimentation, problem solving, and deeper understanding of modern engineering systems, making it a valuable tool for STEM education.
