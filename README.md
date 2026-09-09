# 💡 Smart Light — ESP32 IoT Lighting System

An ESP32-based intelligent lighting system combining
ambient-light sensing, motion detection, addressable LEDs,
OLED monitoring and Wi-Fi web control.

## 🚀 Features

- ESP32-based controller
- 60 WS2812B individually addressable LEDs
- LDR-based ambient light detection
- PIR motion detection
- Automatic brightness control
- OLED status display
- Wi-Fi web control
- Manual and automatic modes
- Multiple colours
- Rainbow effect
- Flow effect
- Mobile-friendly web interface

## 🔧 Hardware

- ESP32
- 60 × WS2812B LEDs
- LDR
- 10kΩ resistor
- PIR sensor
- 0.96" OLED
- External 5V power supply

## 📌 Pin Configuration

| Component | ESP32 Pin |
|---|---|
| WS2812B DIN | GPIO 5 |
| LDR | GPIO 34 |
| PIR OUT | GPIO 27 |
| OLED SDA | GPIO 21 |
| OLED SCL | GPIO 22 |

## 📱 Web Interface

The ESP32 creates a Wi-Fi network and hosts
a web-based control interface for the lighting system.

## ⚙️ Working

LDR → Ambient light detection  
PIR → Motion detection  
ESP32 → Processing and control  
WS2812B → Lighting output  
OLED → Local status display  
Wi-Fi → Smartphone control

## 🔮 Future Scope

- Cloud connectivity
- Dedicated mobile application
- Energy monitoring
- Voice control
- Scheduling
- Multi-room lighting
