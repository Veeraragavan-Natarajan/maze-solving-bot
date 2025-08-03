# VR MazeSolver - Autonomous Maze Solving Robot


> A smart and compact robot designed to autonomously navigate through mazes using IR and ultrasonic sensors.

---

## 🚀 Project Overview
The **VR MazeSolver** is a line-and-obstacle-detecting robot developed using Arduino that intelligently navigates mazes using sensor feedback and conditional logic. It uses IR sensors to follow pathways and an ultrasonic sensor with a servo to scan for obstacles, adjusting its path dynamically.

---

## 🧠 Features
- Dual IR sensors for wall/path detection
- Ultrasonic sensor mounted on a servo for multi-directional scanning
- Adaptive direction choosing algorithm
- Smooth obstacle avoidance and sharp turn handling
- Simple and effective Arduino-based logic

---

## 🔩 Hardware Used
- Arduino UNO
- L298N Motor Driver
- 2x BO Motors
- 2x IR Sensors
- HC-SR04 Ultrasonic Sensor
- Servo Motor (SG90 or compatible)
- Chassis & Wheels
- 9V or 12V Battery Pack

---

## 🧾 How It Works

1. **Path Following**:  
   The IR sensors are positioned to detect dark lines (or wall edges), helping the bot stay aligned on the track.

2. **Obstacle Detection & Navigation**:  
   - When an obstacle is detected in front (closer than a certain distance), the servo rotates the ultrasonic sensor to scan left, center, and right.
   - It measures distances at all three directions.
   - Based on the largest available distance, it rotates or moves accordingly.

3. **Decision Making**:  
   - If front is clear: Go straight.  
   - If front is blocked and left is clear: Turn left.  
   - If left is blocked and right is clear: Turn right.  
   - If all directions blocked: Stop or reverse (optional fallback).

---

## 🧑‍💻 Author & Credits
**Veeraragavan Natarajan**  
- 🧠 Robotics Developer | Embedded Systems | Innovator  
- 📸 Instagram: [@veerzz_23](https://instagram.com/veerzz_23)  
- 💻 GitHub: [Veeraragavan-Natarajan](https://github.com/Veeraragavan-Natarajan)

---

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🌟 Status: Completed ✅

