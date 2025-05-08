# 📷 ESP32-CAM Surveillance System

![ESP32-CAM](https://github.com/jhherre3/ESP32-CAM-Surveillance/blob/main/Files/esp32-cam.jpg)

Welcome to the **ESP32-CAM Surveillance Repository**, featuring projects built using the affordable and powerful AI-Thinker ESP32-CAM module. This project transforms the board into a compact Wi-Fi-enabled surveillance camera for IoT and smart home systems.

---

## 🧠 Board Overview

The **ESP32-CAM (AI-Thinker)** is a microcontroller board with built-in camera support, Wi-Fi/Bluetooth connectivity, and GPIO access, making it ideal for low-cost image and video applications.

### ⚙️ Core Features

- **ESP32-S Camera Module** (AI-Thinker)
- **OV2640 2MP Camera Sensor**
- **Wi-Fi 802.11 b/g/n** with integrated PCB antenna
- **MicroSD Card Slot** for storage
- **GPIO Access** for motion sensors, relays, and more
- **Ultra-low power sleep support**
- **Can integrate with ESPHome, Home Assistant, or MQTT**

---

## 🛠️ Programming Notes

To flash code via USB using an FTDI programmer:

### 🔌 Wiring (FTDI to ESP32-CAM):

| FTDI Pin | ESP32-CAM Pin |
|----------|----------------|
| 5V       | 5V             |
| GND      | GND            |
| TX       | U0R            |
| RX       | U0T            |

> ✅ **Important:**  
To enter flash mode:
- Hold **IO0** (once the sketch is compiled before it completes)
- Press **RST** after to reset

In Arduino IDE:
- Select **Board**: `AI Thinker ESP32-CAM`
- Choose proper COM port
- Upload your sketch and press **RST** again to start

---

## 🌐 Project Capabilities

This ESP32-CAM project is designed for live video surveillance and can serve over:

- 📺 **Built-in web server** stream (via Arduino sketch)
- 🏠 **ESPHome integration** for Home Assistant  
- 🌍 **IoT cloud dashboards** (using MQTT or REST)
- 💾 Optional MicroSD storage for snapshots or logs

---

## 🧪 Project Goals

- 📷 **Live camera feed via Wi-Fi**
- 📡 **Optional MQTT or Home Assistant triggers**
- 🔐 **Future: Password protection or face detection**
- 🧰 **GPIO expansion** for PIR sensors, LEDs, and relays

---

## 📂 Repository Structure

