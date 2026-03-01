# ESP32-WROOM Fan Controller System

An ESP32-based embedded system that controls a fan based on temperature and humidity readings from a DHT11 sensor, with a web interface.

## 🔧 Hardware Components
- ESP32-WROOM controller
- DHT11 temperature and humidity sensor
- 5V fan (0.19A)
- IRL540N MOSFET
- 1N4007 protection diode
- Breadboard power module

## 🔌 Wiring Diagram
- DHT11 data → GPIO26
- MOSFET gate (PWM) → GPIO25
- Fan power → 5V
- Common GND

## 🌡️ Operation
- Automatic mode: fan turns on if temperature > 26°C OR humidity > 70%
- Manual control via web interface
- PWM speed control for the fan

## 📱 Web Interface Features
- Real-time temperature and humidity display
- Fan on/off control
- Speed control slider

## 📦 Installation
1. Follow the wiring diagram
2. Install Arduino IDE with ESP32 support
3. Install DHT sensor library
4. Upload the code to ESP32
5. Connect to the server IP address in your browser
