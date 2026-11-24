# Green-Wave-Emergency-Siren-Classifier
AI and IoT-based smart traffic management system using machine learning for emergency siren detection and ESP32-based traffic signal control.
# 🚨 Green Wave – Emergency Siren Audio Classifier

### AI and IoT Based Smart Traffic Management System

An intelligent traffic management project that aims to detect emergency vehicle sirens using Artificial Intelligence and Machine Learning and provide traffic signal priority through an ESP32-based controller.

---

## 📌 Project Overview

Green Wave is an AI and IoT-based smart traffic management system designed to help emergency vehicles such as ambulances, fire brigades and police vehicles move through traffic more efficiently.

The project uses a trained AI/ML audio classification model to distinguish emergency sirens from normal environmental and city noise.

When an emergency siren is detected, the proposed system uses an ESP32 microcontroller to control traffic signal LEDs and demonstrate a temporary Green Wave for the emergency vehicle's direction.

The traffic signals are intended to return to normal operation after the emergency vehicle passes.

## 🎯 Objectives

- Develop an AI-based emergency siren detection system.
- Classify emergency sirens and normal environmental sounds.
- Use Machine Learning for audio classification.
- Integrate AI-based detection with an ESP32 controller.
- Demonstrate emergency vehicle priority using traffic signal LEDs.
- Explore IoT-based intelligent traffic management.

## ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | AI/ML model development |
| Machine Learning | Audio classification |
| CNN | Audio classification architecture, if used |
| ESP32 | Embedded system controller |
| Arduino IDE | ESP32 programming |
| Edge Impulse | Model training, if used |
| IoT | Smart traffic signal control |

## 🔌 Hardware Components

The following components have been purchased for the prototype:

- ESP32 Development Board
- Breadboard
- Red LED
- Yellow LED
- Green LED
- Jumper Wires
- Resistors
- Additional audio sensing hardware (to be confirmed)

## 🧠 AI/ML Model

Our team has trained an AI/ML model for emergency siren audio classification.

The model is intended to identify emergency vehicle sounds and distinguish them from background noise.

**Model Details:**
- Training Platform: [Add actual platform]
- Model Architecture: [Add actual architecture]
- Dataset: [Add dataset details]
- Classes: [Add actual classes]
- Model Accuracy: [Add actual result]

## 🔄 Proposed Working Principle

1. A microphone captures surrounding audio.
2. The trained AI model processes the audio.
3. The model identifies emergency sirens or normal noise.
4. The classification output is passed to the controller.
5. ESP32 controls the traffic signal LEDs.
6. A Green Wave is demonstrated for the emergency vehicle's direction.
7. Normal traffic signal operation resumes.

## 🏗️ Project Development Status

| Project Activity | Status |
|---|---|
| Project concept selection | Completed |
| Hardware component purchase | Completed |
| AI/ML model training | Completed |
| Hardware circuit assembly | In Progress |
| Microphone integration | Pending |
| Model deployment and hardware integration | Pending |
| Complete prototype testing | Pending |

*Status will be updated as development progresses.*

## 📁 Repository Structure

```text
Green-Wave-Emergency-Siren-Classifier/
│
├── README.md
│
├── hardware/
│   ├── circuit_diagram/
│   ├── component_images/
│   └── connections.md
│
├── software/
│   ├── esp32_code/
│   └── requirements.txt
│
├── ai_model/
│   ├── training_code/
│   ├── trained_model/
│   └── model_details.md
│
├── dataset/
│   └── README.md
│
├── documentation/
│   ├── project_report/
│   ├── literature_review/
│   └── project_photos/
│
└── results/
    └── testing_results.md
```

## 🚀 Future Scope

- Improve siren detection in noisy environments.
- Support multiple emergency vehicle siren categories.
- Integrate real-time audio processing.
- Deploy the trained model on a suitable embedded platform.
- Implement multi-intersection Green Wave coordination.
- Explore GPS-based emergency vehicle location tracking.

## 👨‍💻 Project Team

**Harsh Kumar**  
B.Tech – Computer Science and Engineering 
IILM University, Gurugram

**Group Members:**
Karan Singh 
Tanish singh

## 📚 Academic Information

- University: IILM University, Gurugram
- Course: B.Tech CSE 
- Subject: IoT and Robotics
- Course Code: CSE25309

## 📌 Note

This project is being developed as an academic engineering prototype. The AI/ML model has been trained, while hardware integration and complete system testing are being developed.

---

**Green Wave – Making Traffic Smarter for Emergency Response.** 🚑
