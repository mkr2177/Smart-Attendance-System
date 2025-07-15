# Smart-Attendance-System
This project is a smart classroom entry and attendance solution built using Arduino and IoT components. It automates the attendance process and ensures secure gate control using RFID, Ultrasonic Sensor, LCD Display, Servo Motor, and a Keypad system for teacher authentication.
📚 RFID + IoT Based Smart Attendance & Entry System
This project is a smart classroom entry and attendance solution built using Arduino and IoT components. It automates the attendance process and ensures secure gate control using RFID, Ultrasonic Sensor, LCD Display, Servo Motor, and a Keypad system for teacher authentication.

🔧 Technologies & Components Used
Arduino UNO
RFID Module (RC522)
Ultrasonic Sensor (HC-SR04)
Servo Motor
16x2 I2C LCD
4x4 Keypad
Push Button
Buzzer
Breadboard + Jumper Wires
🚀 Features
✅ Automated Student Attendance via RFID Tag scanning
🚪 Gate Unlock System for students with valid RFID
🔢 Keypad-Based Password Entry for teacher access from inside
📏 Ultrasonic Sensor to detect a person at the gate
📟 LCD Display showing system status (Welcome, Invalid Card, Gate Open, etc.)
🔒 Security & Access Control for both students and teachers
🎥 Project Walkthrough
Watch the complete working demo on YouTube:
▶️ IoT + RFID Attendance System Demo

🔧 Working Logic
A student taps their RFID card on the reader.
The system checks if the RFID tag is valid.
If valid:
The gate opens via a servo motor.
A 5-second timer starts.
During this time, an ultrasonic sensor (placed inside the class) checks if the student has actually entered.
After 5 seconds:
The gate closes automatically.
The student cannot exit back immediately.
Attendance is marked for the student only if they enter within the 5-second time frame.
🔐 Future Improvements
Cloud integration for storing attendance data.
Admin dashboard for real-time attendance.
SMS/Email alerts on invalid access.
Face recognition as an additional layer.
