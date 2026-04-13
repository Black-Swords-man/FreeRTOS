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
- **Task Management**
  - Task creation (`xTaskCreate`, `xTaskCreatePinnedToCore`)
  - Task scheduling and delays (`vTaskDelay`, `pdMS_TO_TICKS`)
  - Task priorities and dual‑core execution (ESP32 specific)
  - Stack monitoring (`uxTaskGetStackHighWaterMark`)

- **Inter‑Task Communication**
  - Queues for passing simple data (integers) between tasks
  - Queues for passing structured data (e.g., sensor structs)
  - Safe communication without global variables
  - Foundation for synchronization and resource sharing

---

## Repository Structure
```
FreeRTOS/
  01_Single_Task/
    01_Single_Task.ino
    README.md
  02_Multi_Tasking/
    02_Multi_Tasking.ino
    README.md
    serial_output.png
  03_Dual_Core/
    03_Dual_Core.ino
    README.md
    serial_output.png
  04_Queue/
    04_Queue.ino
    README.md
    serial_output.png
  05_Queue_Struct/
    05_Queue_Struct.ino
    README.md
    serial_output.png
  (future exercises will be added here)
```

---

## Author
**Dhayalan R**  

