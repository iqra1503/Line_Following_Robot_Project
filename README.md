# Line Following Robot (LFR)

## 📌 Project Overview
This project presents the design and implementation of a **Line Following Robot (LFR)** using **Arduino Uno**.  
The robot is capable of autonomously following a black line on a white surface using a **5-channel IR sensor array**.  
It can smoothly navigate curves, sharp turns, intersections, and dashed paths using **PID-based motor control**.

This project was developed as part of the **Electronic Shop Practice (ECE 2200)** course at **Rajshahi University of Engineering & Technology (RUET)**.

---

## 🎯 Objectives
- Design and build a functional line-following robot
- Accurately detect and follow black lines
- Execute **45° and 90° turns**
- Cross dashed or broken paths
- Implement **PWM speed control** using Arduino
- Apply **PID control** for smooth movement
- Gain hands-on experience in robotics and embedded systems

---

## 🛠️ Hardware Components
- Arduino Uno  
- TCRT5000 5-Channel IR Sensor Array  
- L298N Motor Driver  
- N20 DC Gear Motors (2)  
- Rubber Wheels (2)  
- Ball Caster  
- 3.7V Li-ion Batteries (2)  
- Battery Holder  
- Switch  
- Robot Chassis  
- Jumper Wires  

---

## 💻 Software Used
- **Arduino IDE**
- Programming Language: **C / C++**

---

## ⚙️ Working Principle
- IR sensors detect the black line by measuring reflected infrared light.
- Sensor data is processed by the Arduino Uno.
- An error value is calculated based on line deviation.
- A **PID control algorithm** generates correction signals.
- The L298N motor driver adjusts motor speed and direction using PWM.
- The robot moves forward, turns left/right, or re-centers itself accordingly.

---

## 🧠 Control Logic
| Sensor Pattern | Action |
|----------------|--------|
| Center detected | Move straight |
| Left deviation | Turn right |
| Right deviation | Turn left |
| No detection | Rotate until line is found |

---

## 📐 Mechanical Design
- Differential drive system with two DC motors
- Ball caster used for balance and stability
- Sensors placed at the front for accurate detection
- Lightweight plywood chassis for strength and portability

---

## 📊 Results
- Smooth line following on standard tracks
- Accurate turns at intersections
- Stable movement using PWM motor control
- Effective error correction using PID logic

---

## ⚠️ Limitations
- Sensitive to lighting conditions
- Performance varies on reflective or uneven surfaces
- Limited battery life
- No obstacle detection

---

## 🚀 Future Improvements
- Obstacle avoidance using ultrasonic sensors
- Wireless monitoring via Bluetooth or WiFi
- LCD or OLED display for real-time data
- Advanced adaptive control algorithms
- Improved power management system

---

