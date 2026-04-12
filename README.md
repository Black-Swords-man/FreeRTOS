# FreeRTOS on ESP32 – Learning Exercises

## Overview
This repository is dedicated to exploring and practicing **FreeRTOS concepts** on the ESP32‑WROOM‑DA module.  
The goal is to build a strong foundation in real‑time operating systems by implementing small, focused exercises that demonstrate multitasking, scheduling, synchronization, and resource management.  

Each exercise is documented with:
- **Code** → Arduino/ESP32 FreeRTOS implementation
- **README** → Explanation of concepts, commands used, expected output, and learning outcomes
- **Structure** → Organized folders for each exercise to show progression

---

## Hardware/Software Requirements
- ESP32‑WROOM‑DA Module
- Arduino IDE
- FreeRTOS (ESP32 Arduino core)
- Serial Monitor for debugging

---

## Core Concepts Covered
- **Task Creation** (`xTaskCreate`, `xTaskCreatePinnedToCore`)
- **Task Scheduling & Delays** (`vTaskDelay`, `pdMS_TO_TICKS`)
- **Multitasking & Priorities**
- **Dual‑Core Execution** (ESP32 specific)
- **Stack Monitoring** (`uxTaskGetStackHighWaterMark`)
- **Synchronization** (Mutexes, Queues, Logging tasks – upcoming)

---

## Repository Structure
```
FreeRTOS/
  01_Single_Task/
    code.ino
    README.md
  02_Multi_Tasking/
    code.ino
    README.md
    serial_output.png
  03_Dual_Core/
    code.ino
    README.md
    serial_output.png
  (future exercises will be added here)
```

---

## Author
**Dhayalan R**  

