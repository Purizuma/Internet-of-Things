# 🌫️ Arduino IoT – Gas Detection with MQ135

This project enables gas concentration monitoring using the MQ135 sensor and Arduino. Designed for IoT integration, environmental sensing, and reproducible documentation, it supports real-time alerts and remote data visualization.

## ⚙️ Features

- Detects air pollutants (CO₂, NH₃, benzene, smoke, etc.)
- Analog signal processing with configurable thresholds
- Optional buzzer/LED for local alerts
- MQTT-ready for remote dashboards (Node-RED, Grafana)
- Modular and scalable codebase for IoT deployment

## 🛠️ Hardware Requirements

- Arduino Uno/Nano/ESP8266/ESP32
- MQ135 Gas Sensor
- Breadboard and jumper wires
- Optional: buzzer, LED, Wi-Fi module or Ethernet shield

## 📁 Folder Structure

Arduino_IoT_GasDetection_MQ135/ ├── MQ135_GasSensor.ino           
  # Main Arduino sketch ├── config.h
  # Thresholds and pin configuration ├── mqtt_publish.ino
  # MQTT integration (optional) ├── docs/ │   └── wiring_diagram.png
  # Sensor connection schematic └── README.md
  # Project overview

## 📊 Sensor Calibration

MQ135 requires burn-in and calibration for accurate readings. Use `config.h` to adjust:

- Baseline voltage (clean air)
- Detection thresholds (ppm estimation)
- Alert behavior and sensor pin mapping

## 🌐 IoT Integration

Supports MQTT publishing for remote monitoring. Compatible with:

- Node-RED dashboards
- Arduino Cloud

## 📚 Documentation & Reproducibility

All configurations and experiments are documented to ensure reproducibility. Contributions are welcome to expand use cases, improve calibration, and enhance community impact.

## 👤 Author

Maintained by **Antonius** — passionate about open-source IoT systems, reproducible technical documentation, and community-driven innovation.

---

Feel free to fork, adapt, and share your improvements. Let’s build smarter, cleaner environments together through modular design and open collaboration!
