# 🔍 Line Following Robot using Arduino

This project is a line-following robot built using Arduino, IR sensors, and a motor driver module. It follows a black path over a white surface using sensor-based navigation.

## 🚀 Features
- Follows black lines on white surfaces
- Simple and reliable navigation
- Built using low-cost components
- Bluetooth controllable (optional)

## 🛠️ Tools & Technologies Used
- Arduino Uno
- L298N Motor Driver
- IR Line Sensors
- HC-05 Bluetooth Module (optional)
- Embedded C (Arduino IDE)
- Tinkercad / Proteus for simulation
- USB for power/debugging

## ⚙️ Hardware Components
| Component             | Quantity |
|----------------------|----------|
| Arduino UNO          | 1        |
| IR Sensor Module     | 2        |
| L298N Motor Driver   | 1        |
| DC Motors with Wheels| 4        |
| Chassis              | 1        |
| Battery Pack (18650) | 1        |
| HC-05 Bluetooth Module (optional)| 1 |
| Jumper Wires         | As needed |

## 📷 Circuit Diagram & Robot
### Circuit Diagram
![Circuit Diagram](./Screenshot%202025-07-27%20121351.png)

### Actual Robot Car
![Robot Car](./Screenshot%202025-07-27%20121404.png)

## 📁 Project Structure

Line-Following-Robot/
├── line_follow.ino # Arduino code
├── README.md # Project documentation
├── Screenshot 2025-07-27 121351.png # Circuit diagram
├── Screenshot 2025-07-27 121404.png # Robot image
├── Mini_Project_Line_Solving_robot-report.pdf # Project report


## 🧠 Working Principle
The robot uses two IR sensors to detect the black line. Depending on sensor output:
- If both sensors detect white: move forward
- If left sensor sees black: turn left
- If right sensor sees black: turn right
- If both see black: stop or make a U-turn

## 📜 How to Run
1. Upload `line_follow.ino` to your Arduino Uno using Arduino IDE.
2. Power the robot using a battery or USB.
3. Place the robot on a black line over white surface.
4. Watch it follow the path autonomously.

## 🧑‍💻 Author
- **Name:** Mohammed Sinan
- **Field:** ECE Engineer | Embedded Systems Enthusiast

## 📌 License
This project is open-source and available under the MIT License.