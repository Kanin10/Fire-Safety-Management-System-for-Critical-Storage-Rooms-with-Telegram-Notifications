# Fire-Safety-Management-System-for-Critical-Storage-Rooms-with-Telegram-Notifications
IoT Fire Safety Management System using ESP32, MQ-2 sensor, and Telegram Bot API

An automated IoT smoke and gas detection system designed for critical storage rooms. This project utilizes an ESP32 microcontroller integrated with an MQ-2 sensor to provide real-time environmental monitoring, instant emergency notifications via Telegram, and comprehensive data visualization across multiple IoT platforms including **Node-RED**, **ThingsBoard**, and **Blynk**.

## 🌟 Key Features
* **Real-time Smoke Detection:** Utilizes the MQ-2 sensor to detect smoke and combustible gases accurately.
* **Multi-Platform Visualization:** Displays live sensor data and system status simultaneously on three distinct dashboards (**Node-RED**, **ThingsBoard**, and **Blynk**) to support versatile monitoring environments.
* **Instant Notifications:** Integrates with the Telegram Bot API to send immediate alert messages directly to the user's smartphone upon detecting hazardous conditions.
* **Data Workflow & Integration:** Configured robust data routing and simulated workflows to enhance facility safety management.

## 🛠️ Hardware & Software
* **Microcontroller:** ESP32
* **Sensor:** MQ-2
* **Dashboards & IoT Platforms:** Node-RED, ThingsBoard, Blynk IoT
* **Software/Tools:** VS Code (ESP Home)
* **API Integration:** Telegram Bot API

## ⚙️ How it works
1. The MQ-2 sensor continuously monitors the air quality in the storage facility.
2. The ESP32 processes the sensor data and transmits it via Wi-Fi to the integrated IoT platforms (**Node-RED, ThingsBoard, Blynk**) for real-time visualization and logging.
3. If the smoke/gas concentration exceeds the predefined safety threshold, the ESP32 instantly triggers an HTTP request to the Telegram API, dispatching an emergency alert message to the designated safety group.
