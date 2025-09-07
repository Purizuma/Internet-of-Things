# 🔌 Arduino IoT – ACS712 Current Sensor

This folder contains modular Arduino-based code and documentation for measuring electrical current using the ACS712 sensor. Designed for IoT integration, remote monitoring, and reproducible experimentation.

## 📦 Features

- Real-time current sensing with ACS712
- Calibrated analog readings with noise filtering
- MQTT-ready data output for IoT dashboards
- Compatible with Node-RED, Grafana, and Ubuntu Server setups
- Modular codebase for easy adaptation and scaling

## 🛠️ Hardware Requirements

- Arduino Uno R4 Wifi /
- ACS712 Current Sensor (5A / 20A / 30A variant)
- Breadboard and jumper wires
- Optional: Wi-Fi module or Ethernet shield for IoT connectivity

## 📁 Folder Structure
Arduino_IoT ACS712_CurrentSensor.ino       
- Main Arduino sketch
- Sensor calibration and pin config
- Optional MQTT integration
- Sensor connection schematic
- Project overview

## 📊 Calibration & Accuracy

The ACS712 outputs a voltage proportional to current. Calibration is essential for accurate readings. Use the `config.h` file to adjust:

- Zero-current voltage offset
- Sensitivity (mV/A) based on sensor variant

## 🌐 IoT Integration

This project supports MQTT publishing for remote monitoring. You can visualize current data in:

- Node-RED dashboards
- Arduino Cloud

## 📚 Documentation

All experiments and configurations are documented to ensure reproducibility. Contributions and forks are welcome to expand use cases and improve accuracy.

## 🧠 Author

Maintained by **Antonius** — passionate about modular IoT systems, open-source documentation, and community-driven innovation.

---

Feel free to fork, adapt, and share your improvements. Let’s empower technical communities through reproducible design!
