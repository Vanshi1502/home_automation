# Home Automation using NodeMCU ESP8266

This repository contains the code and documentation for a **Home Automation System** developed as part of the IEEE NITK Virtual Expo 2025.

> 📎 [Google Doc Report](https://docs.google.com/document/d/1IlZARPONXjj3gcUax8LSd8hJbKoHa6KjGI96FxYVvE8/edit)  
> 🔗 [IEEE Virtual Expo Report](https://ieee.nitk.ac.in/virtual_expo/report/118)

---

## 🔧 What It Does

- Controls electrical appliances (fan, light) using NodeMCU
- Interfaced with a relay and motor driver
- Controlled via WiFi and manual buttons
- Utilizes DHT11 for temperature & humidity sensing

---

## 🛠️ Hardware Used

- NodeMCU ESP8266
- Relay Module
- L293D Motor Driver
- DHT11 Sensor
- Fan & LED
- Push Buttons
- Breadboard + Jumper Wires

---

## 💻 Code

You’ll find the Arduino/ESP code in the [`code/`](./code/) folder.

---

## 🚀 Setup Instructions

1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/home-automation-iot.git
   cd home-automation-iot
   ```

2. Open `main.ino` in the Arduino IDE

3. Install required libraries (e.g., `DHT`, `ESP8266WiFi`, etc.)

4. Connect hardware as per the report diagram

5. Upload the code to NodeMCU and power the circuit

---

## 📷 Demo & Documentation

Detailed documentation and implementation steps are available in the links below:

- [IEEE Project Page](https://ieee.nitk.ac.in/virtual_expo/report/118)
- [Google Docs Report](https://docs.google.com/document/d/1IlZARPONXjj3gcUax8LSd8hJbKoHa6KjGI96FxYVvE8/edit)

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).
