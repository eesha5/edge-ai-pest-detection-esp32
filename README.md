# 🐛 Edge AI Pest Detection System using ESP32-CAM

An Edge AI based pest detection system capable of performing real-time image classification using **TensorFlow Lite Micro** deployed on an **ESP32-CAM**.

This project was developed as part of the Robotics & Automation Tinker Programme to demonstrate how Machine Learning models can be deployed on resource-constrained embedded hardware for agricultural applications.

---

## 🚀 Features

- Real-time pest detection on ESP32-CAM
- TensorFlow Lite Micro inference
- On-device image classification
- Camera-based pest recognition
- IR sensor based object detection
- OLED display for user feedback
- Buzzer alert system
- Edge AI deployment without cloud connectivity

- ---

# 🛠 Hardware Components

- ESP32-CAM
- Arduino Uno (Functionality Demonstration)
- IR Sensor
- OLED Display (I2C)
- Active Buzzer
- Breadboard & Jumper Wires

---

# 💻 Software & Technologies

- Python
- TensorFlow
- TensorFlow Lite
- TensorFlow Lite Micro
- Arduino IDE
- Embedded C++
- ESP32 Camera Library
- Edge AI
- Computer Vision

---

# 🧠 Project Workflow

```text
Pest Image Dataset
        │
        ▼
Train CNN Model (TensorFlow)
        │
        ▼
Convert to TensorFlow Lite (.tflite)
        │
        ▼
Convert Model to C Header (.h)
        │
        ▼
Deploy on ESP32-CAM
        │
        ▼
Capture Live Image
        │
        ▼
Run On-device Inference
        │
        ▼
Pest Detected?
      ┌──────┴──────┐
      ▼             ▼
 OLED Display    Buzzer Alert
```
