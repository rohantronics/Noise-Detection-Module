# Noise-Detection-Module
Welcome to the repository for my Smart Noise Detection and Classification System — a custom-designed PCB and embedded firmware stack that detects, classifies, and reports noise events in real time. This project is ideal for silent zones such as libraries, meditation centers, study rooms, or offices, where maintaining silence is important.
# Overview
This project features a fully custom PCB powered by the ESP32-S3-WROOM-1-N8R8 module and a MEMS microphone, designed to detect and classify sound sources like voices, fans, or tools (e.g., drills). Leveraging TensorFlow Lite and I2S audio, this board performs on-device AI inference to minimize latency and avoid cloud processing. 
# 🎯Problem Statement
In quiet public spaces like:

> Libraries

> Meditation halls

> Classrooms

...even small disturbances can break focus. Traditional noise meters lack the intelligence to understand the type of noise or to alert the right personnel in real time.
# 💡Solution
This board uses real-time AI at the edge to:

> Detect and classify sounds: voice, fan, drilling, etc.

> Notify appropriate authorities (e.g., librarians, staff)

> Run offline, without constant cloud connectivity

Maintain low power with battery support
# Key Features
👂 Noise Detection & Classification

> Trained TinyML model with TensorFlow Lite

> Captures audio via I2S MEMS mic

> Classifies in real-time: voice, fan, drill, silence, etc.

📲 Connectivity
> Wi-Fi or BLE communication to send alerts or logs

> OTA-ready architecture (firmware upgradable wirelessly)

🔋 Portable & Low Power
> Battery-operated with onboard charging and protection

> Power-efficient for real-world deployment
# Hardware Highlights
Component	Function
> ESP32-S3-WROOM-1-N8R8	AI acceleration, native USB, Wi-Fi + BLE
> SPH0645LM4H-B	High-quality I2S MEMS microphone
> TP4056 + DW01A-G + FS8205	Li-ion battery charging & protection
> AP2114 LDO	3.3V low-dropout linear voltage regulator
# Screenshots

![image](https://github.com/user-attachments/assets/59874362-b1ff-442a-ab86-fa713970a079)  ![image](https://github.com/user-attachments/assets/2a0cdebd-686d-48ba-b7f6-504c5b5eb8ca)



![3D view 1](https://github.com/user-attachments/assets/29332958-6963-4d16-a4ec-44cb6d4109a4)  ![3D view 2](https://github.com/user-attachments/assets/a30f0433-cb86-4255-ae98-3a59fa31e86f)
![3D view](https://github.com/user-attachments/assets/7eb0b7d1-6ab1-4b3f-b1e3-64d9a00e376c)



