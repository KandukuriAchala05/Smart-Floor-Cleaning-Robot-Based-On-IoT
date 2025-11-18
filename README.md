🤖 Smart Floor Cleaning Robot Based on IoT

A mini-project developed as part of the Bachelor of Technology curriculum in the Department of Electronics & Communication Engineering.
This project focuses on building an autonomous, IoT-enabled floor cleaning robot capable of navigating indoor environments, detecting obstacles, cleaning surfaces, and enabling remote monitoring through the Internet of Things.

📌 Project Overview

Manual floor cleaning is time-consuming and inefficient, especially in large indoor spaces such as hostels, offices, and labs.
This project introduces a smart IoT-based floor cleaning robot that uses sensor-driven navigation and remotely controllable features to automate the cleaning process.

The robot is designed to:

Navigate automatically

Avoid obstacles

Perform wet/dry cleaning

Send cleaning status to the cloud

Allow remote monitoring and control

🚀 Features

🤖 Autonomous Navigation
Uses IR/Ultrasonic sensors to detect obstacles and change direction.

🧹 Dual Cleaning Modes

Dry cleaning (rotating brushes)

Wet cleaning (water/sanitizer tank + pump mechanism)

📶 IoT-Based Control and Monitoring

Start/stop through smartphone

Status updates to cloud (ThingSpeak/Blynk)

🔋 Battery-Powered
Rechargeable power system for mobility.

⚠️ Safety Features

Automatic stop on collision

Low battery alert

Overload protection

🗺️ Efficient Path Cleaning
Zig-zag or random navigation pattern for full area coverage.

🧰 Tech Stack
Component	Description
ESP8266 (NodeMCU)	IoT microcontroller for cloud operations
Arduino Uno / ESP32	Motion and sensor control
Ultrasonic/IR Sensors	Obstacle detection
DC Motors + Motor Driver (L298N)	Robot locomotion
Water Pump / Spray Motor	Wet cleaning
Brush Motor	Dry cleaning
ThingSpeak / Blynk	IoT cloud dashboard
Li-ion Battery Pack	Power supply
🛠️ Hardware Components

NodeMCU / ESP32

Arduino Uno (optional dual controller system)

Ultrasonic sensor (HC-SR04) or IR sensors

L298N Motor Driver Module

DC Geared Motors (wheels)

Brush motor for cleaning

Water tank + pump

Chassis / Robot frame

Battery (Li-ion 18650 or lead-acid 12V)

Connecting wires, switches, PCB

💻 Software Tools

Arduino IDE

Blynk / ThingSpeak IoT Platform

Embedded C/C++ (microcontroller firmware)

📊 System Architecture

Sensors continuously scan for obstacles.

The controller adjusts the robot’s direction based on sensor data.

Brush motor and pump operate based on cleaning mode.

ESP8266 sends cleaning status, distance data, and battery level to the cloud.

User can remotely start/stop the robot via IoT app/dashboard.

🧼 Cleaning Mechanism

Dry Cleaning: Rotating brush collects dust and debris.

Wet Cleaning: Water/sanitizer is sprayed, and the rear mop cleans the floor.

Hybrid Mode: Both mechanisms run together for deep cleaning.

🔰 Safety Features

Auto-stop on collision

Water pump turns off automatically when tank is empty

Motor cut-off on overheating

Low battery shutdown

✅ Advantages

Reduces manual labor

Effective for hostels, offices, labs, and homes

Autonomous, intelligent cleaning

Remote monitoring and control

Energy-efficient and low maintenance

🌍 Applications

Smart homes

Hospitals & labs

Hostels and educational institutions

Office spaces

Industrial floors

📅 Future Scope

Integration with AI-based SLAM navigation

Voice control (Google Assistant/Alexa)

Automatic charging dock

Real-time map creation

Mobile app for full robot control
