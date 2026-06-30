# AI-powered-Smart-Stove-Safety


An intelligent IoT-based Smart Stove Safety Monitoring System that combines **ESP32 Bluetooth Low Energy (BLE)** communication with a futuristic web dashboard to monitor kitchen safety in real time.

The system continuously observes stove temperature, flame detection, human presence, buzzer status, gas valve control, and safety alerts to prevent unattended cooking accidents.

---

## 🚀 Features

### 🌡️ Real-Time Sensor Monitoring

- Ambient Temperature
- Stove Surface Temperature
- PIR Motion Detection
- IR Flame Detection

---

### 🤖 AI Safety Monitoring

- Detects unattended cooking
- Calculates Live Safety Score
- Predictive temperature rise warning
- Automatic danger detection

---

### ⏱ Multi-Level Alert System

| Time | Action |
|------|---------|
|10 sec|Voice Alert|
|20 sec|Warning|
|30 sec|Mobile Notification|
|40 sec|Automatic Gas Cutoff|

---

### 🔥 Dashboard Features

- Futuristic Glassmorphism UI
- Dark / Light Theme
- Animated Background
- Live BLE Connection Status
- Signal Strength Indicator
- Toast Notifications
- Voice Alerts
- Session Summary
- Real-Time Charts
- Responsive Design

---

## 🛠 Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript (ES6)

### Libraries

- Chart.js
- Web Bluetooth API
- Speech Synthesis API

### Hardware

- ESP32
- MLX90614 Temperature Sensor
- PIR Motion Sensor
- IR Flame Sensor
- Relay Module
- Buzzer
- LEDs

---

## 📊 Dashboard Overview

The dashboard displays

- Ambient Temperature
- Stove Temperature
- Motion Detection
- Flame Detection
- Safety Score
- Gas Valve Status
- Buzzer Status
- Live Graphs
- Alert Timeline
- Session Statistics

---

## 🔗 Bluetooth Communication

The dashboard connects directly to the ESP32 using BLE.

### Service UUID

```
12345678-1234-5678-1234-56789abcdef0
```

### Characteristics

|Characteristic|Purpose|
|--------------|-------|
|LIVE_CHAR_UUID|Receive Live Sensor Data|
|CONTROL_CHAR_UUID|Send Commands|

---

## 📈 Live Analytics

Two live charts are displayed

- Temperature vs Danger Threshold
- PIR & Flame Activity

Both update continuously while connected.

---

## ⚠ Safety Logic


## 🎨 UI Features

- Glassmorphism Cards
- Animated Floating Logo
- Particle Background
- Responsive Layout
- Smooth Animations
- Neon Effects
- Light & Dark Mode



## 🚀 Getting Started

Clone the repository

```bash
git clone https://github.com/yourusername/Smart-Stove-AI-Dashboard.git
```

Open

```
index.html
```

Allow Bluetooth permissions.

Power on the ESP32 device.

Click

```
Connect Smart Stove
```

Enjoy real-time monitoring.

---

## 📸 Screenshots

### Dashboard

(Add screenshot here)

---

### Dark Theme

(Add screenshot here)

---

### Light Theme

(Add screenshot here)

---

## 🔮 Future Improvements

- Firebase Cloud Logging
- SMS Alerts
- Email Notifications
- AI Fire Prediction
- Mobile App
- Camera-based Object Detection
- Voice Assistant Integration

---

## 👨‍💻 Author

**Kulsum**

---

## ⭐ Support

If you like this project, don't forget to ⭐ the repository.
