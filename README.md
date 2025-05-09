# 🤖 VersaBot

VersaBot is a **semi-autonomous delivery robot** built as a **scaled-down working model** to demonstrate navigation and delivery capabilities in environments such as restaurants, hospitals, and warehouses. It is designed using affordable and accessible components like Arduino and Bluetooth modules and integrates basic obstacle detection, payload handling, and mobile app control.

---

## 🚀 Project Overview

VersaBot is designed to automate item transport tasks with minimal human intervention. Using a combination of ultrasonic and infrared sensors, it can navigate predefined paths, detect obstacles, and safely deliver items via an extendable tray. The system is controlled through a mobile app developed with MIT App Inventor, ensuring intuitive interaction and real-time notifications.

---

## ✨ Features

- ✅ Autonomous navigation via predefined paths
- 🧭 Obstacle detection using ultrasonic sensors
- 📦 Rack-and-pinion-based extendable payload tray
- 📱 Mobile app control (Bluetooth) with live status updates
- 🔐 User authentication & feedback via Firebase
- 🖥 Onboard LCD for displaying robot status

---

## 🧠 Tech Stack

### Hardware
- Arduino Uno
- Ultrasonic Sensor
- Infrared Sensor
- HC-05 Bluetooth Module
- DC Motors & Motor Relays
- Rack & Pinion Tray Mechanism
- 12V Rechargeable Battery Pack
- Buck Converter
- LCD Display

### Software
- Arduino IDE (C/C++)
- MIT App Inventor (Mobile App)
- Firebase (Authentication & Feedback)
- Bluetooth Serial Communication

---

## 🧰 Hardware Components

| Component               | Description                            |
|------------------------|----------------------------------------|
| Arduino Uno            | Main microcontroller                   |
| Ultrasonic Sensor      | Obstacle detection                     |
| IR Sensor              | Payload presence detection             |
| Bluetooth Module (HC-05)| Mobile communication                   |
| DC Motors              | Robot mobility                         |
| Relay Modules          | Motor control                          |
| LCD Display            | Status display                         |
| Rack & Pinion          | Tray extension mechanism               |
| Hylam Sheet            | Base chassis material                  |
| 12V Battery            | Power supply                           |

---

## 🛠️ Setup & Installation

1. **Assemble** hardware as per the structural design.
2. **Upload** Arduino code using the Arduino IDE.
3. **Install** the mobile application (built using MIT App Inventor).
4. **Pair** the mobile device with the HC-05 Bluetooth module.
5. **Login** or Sign Up via Firebase.
6. **Choose a destination** from the app and monitor progress in real time.

---

## ✅ Testing

- **Unit Testing**: Individual hardware and code modules tested.
- **Integration Testing**: Communication between sensors, motors, and app validated.
- **System Testing**: Full robot flow from start to payload delivery verified.
- **User Acceptance Testing**: Field-tested in simulated restaurant and warehouse scenarios.
- **Security Testing**: Firebase authentication validated for data safety.

---

## 🚧 Future Enhancements

- AI-powered dynamic path planning
- LiDAR-based 3D mapping and localization
- Web dashboard for monitoring multiple robots
- IoT cloud integration for diagnostics and updates

---

## 👨‍💻 Team

- **Shawn Sam Varghese** (MGP21UCS135)  
- **Kevin Kizhakekuttu Thomas** (MGP21UCS089)  
- **Sreejith A** (MGP21UCS137)  
- **Midhun Sreenivas** (MGP21UCS071)  

**Project Guide**: Er. Jerrin Sebastian  
**Institution**: Saintgits College of Engineering  
**University**: APJ Abdul Kalam Technological University  
**Year**: 2023–2024

---

## 📄 License

This project was developed for academic purposes. For commercial use or research adaptation, please contact the project authors or guide.

