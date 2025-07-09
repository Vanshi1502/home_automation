# HOME_AUTOMATION
This repository contains the code and documentation for a **Home Automation System** developed as part of the IEEE NITK Virtual Expo 2025.
Features
Remote Appliance Control: Switch lights and fans on/off from anywhere using the Blynk mobile app.

Sensor Integration: Monitor room temperature, humidity (DHT11), and light intensity (LDR) for automated or manual control.

Real-Time Feedback: Immediate status updates and control confirmation.

Modular & Scalable: Easily add more devices or sensors as needed.

Secure Access: Uses authentication tokens for safe cloud connectivity.

Manual Override: Appliances can also be controlled using physical switches.
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
[Blynk App] <--Wi-Fi/Internet--> [Blynk Cloud] <--Wi-Fi--> [NodeMCU ESP8266]
                                                  |            |         |
                                      [DHT11 Sensor]   [LDR Sensor]  [Relay Module]
                                                                      |
                                                           [Fan, Light, etc.]



How It Works
1.Hardware Setup:

NodeMCU is wired to relay modules and sensors.

Relays control the AC appliances; sensors provide environmental data.

2.Software & Connectivity:

NodeMCU runs Arduino code that reads sensors and listens for app commands.

Device connects to Wi-Fi and communicates with the Blynk cloud.

Blynk app (on iOS/Android) provides a dashboard for users to control devices and view sensor data.

3.User Interaction:

Users toggle appliances and monitor sensor readings via the app.

Sensor data can trigger automated actions (e.g., turn on fan if temperature is high).
---

