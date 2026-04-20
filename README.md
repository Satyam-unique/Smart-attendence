# 📡 RFID-Based Smart Attendance System

An IoT-based Smart Attendance System that uses **RFID technology, ESP32, and a Web Dashboard** to automate attendance marking in classrooms.

---

## 🚀 Project Overview

This project replaces traditional manual attendance systems with an automated, fast, and accurate solution.

- 📶 RFID cards scanned using RC522 module  
- ⚡ ESP32 processes data and sends via Wi-Fi  
- 🌐 Web dashboard shows attendance in real-time  
- 📊 Faculty and students can monitor attendance  

---

## 🎯 Objectives

- Automate attendance marking  
- Reduce manual errors  
- Save classroom time  
- Provide real-time tracking  
- Prevent proxy attendance  

---

## 🛠️ Tech Stack

### 🔌 Hardware
- ESP32 Microcontroller  
- RC522 RFID Module  
- RFID Cards/Tags  

### 💻 Software
- Arduino IDE  
- HTML, CSS, JavaScript  
- Firebase (Firestore / Realtime DB)  
- Web APIs  

---

## ⚙️ System Architecture
RFID Card → RC522 → ESP32 → WiFi → Firebase → Web Dashboard

---

## 🔄 Working Principle

1. Student scans RFID card  
2. RC522 reads UID  
3. ESP32 processes UID  
4. Data sent to server  
5. Server verifies student  
6. Attendance marked  
7. Dashboard updates  

---

## 🌐 Features

- ✅ Real-time attendance tracking  
- ✅ Student & Faculty dashboards  
- ✅ RFID-based automation  
- ✅ Secure database storage  
- ✅ Modern UI dashboard  
- ✅ IoT integration  

---

## 🖥️ Web Dashboard Features

- 🔐 Login system (Student / Faculty)  
- 📊 Attendance statistics  
- 📅 Daily schedule  
- 📋 Subject-wise attendance  
- 🔖 RFID scan processing  

---

## 📊 Advantages

- ⏱️ Saves time  
- 🎯 High accuracy  
- 📡 Contactless system  
- 💰 Cost-effective  
- 📈 Scalable  

---

## ⚠️ Limitations

- RFID card dependency  
- Possible proxy attendance  
- Requires internet  
- Basic security  

---

## 🔮 Future Scope

- 📱 Mobile App integration  
- 📷 QR-based attendance  
- ☁️ Cloud scaling  
- 🤖 AI-based analytics  

---

## 📂 Project Structure
├── hardware/
│ ├── esp32_code.ino
│ └── wiring_diagram.png
├── web/
│ ├── index.html
│ ├── style.css
│ └── script.js
├── docs/
│ └── project_report.pdf
└── README.md

---

## 📜 License

This project is for academic purposes.  
You can use and modify it with proper credit.

---

## ⭐ Support

If you like this project:

- ⭐ Star the repo  
- 🍴 Fork it  
- 💡 Contribute  

---
