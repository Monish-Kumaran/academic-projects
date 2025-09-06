# 🚗 Vehicle-to-Vehicle (V2V) Communication System

## 📖 Overview
This project demonstrates a **V2V communication prototype** for road safety using ESP32 boards.  
It enables one vehicle to send a **brake alert** to another in case of sudden deceleration, helping prevent collisions.

---

## 🛠️ Tools & Technologies
- **Hardware:** ESP32, MPU6050 Accelerometer, GPS Module (Neo-6M, optional), Ultrasonic Sensor (HC-SR04), Buzzer, LED, DC Motors, Motor Driver  
- **Software:** Arduino IDE, WiFi + WiFiUDP libraries, I2Cdev library  
- **Communication:** Wi-Fi (UDP Protocol)

---

## ⚙️ Features
- Sudden brake detection using MPU6050  
- Wireless transmission of braking alert  
- Driver warning with buzzer + LED  
- Obstacle detection using ultrasonic sensor  
- Autonomous response via DC motors  

---

## ▶️ How to Run
1. Upload transmitter code to ESP32 (with MPU6050 + GPS).  
2. Upload receiver code to ESP32 (with LED, buzzer, ultrasonic sensor, motors).  
3. Power both vehicles → simulate braking → observe response.  

---

## 📌 Applications
- Intelligent Transportation Systems (ITS)  
- Low-cost collision avoidance  
- Educational demonstration for V2V protocols  

---
