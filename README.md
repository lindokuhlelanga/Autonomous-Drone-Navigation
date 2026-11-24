# Autonomous Drone Navigation & AI Monitoring System

A Computer Engineering project that integrates **Python, YOLOv8, OpenCV, PyQt5, Arduino, serial communication and Telegram alerts** into a real-time monitoring and navigation prototype.

## Project overview

The system combines computer vision, hardware-software integration and real-time monitoring. A YOLOv8n model is used for object/person detection, while a PyQt5 interface provides live status and control. Arduino hardware provides external visual feedback through serial communication, and Telegram alerts support remote notification.

## Key results

- **87% object-detection accuracy** during project testing
- **Detection latency below 1.5 seconds** on standard PC processing
- **10–12 minutes validated operation** per battery cycle
- Prototype implemented within a **R2,920 project budget**
- Multi-system integration across Wi-Fi, serial communication, computer vision and Telegram API

## Technologies

- Python
- YOLOv8 / Ultralytics
- OpenCV
- PyQt5
- PySerial / UART
- Arduino / C++
- Telegram Bot API
- DJI Tello / IP video stream
- Multithreading

## System architecture

The project is organised around three functional layers:

1. **Perception** — camera/video input and YOLOv8 object detection
2. **Decision and monitoring** — application logic, status handling and alerts
3. **Hardware/control** — drone/Arduino integration and user controls

## Repository status

The public repository is being prepared from the completed academic project. Source code, screenshots, diagrams and setup documentation will be added after removing credentials and university-specific submission information.

## Planned public structure

```
.
├── src/                  # Python application modules
├── arduino/              # Arduino firmware
├── docs/                 # Architecture and technical notes
├── screenshots/          # GUI, detection and alert evidence
├── requirements.txt      # Python dependencies
├── .gitignore            # Secrets, environments and generated files
└── README.md
```

## Security note

API keys, Telegram bot tokens, Wi-Fi credentials and personal data are intentionally excluded from the public repository.
