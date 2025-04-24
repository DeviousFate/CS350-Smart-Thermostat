# CS350-Smart-Thermostat
This was the final project of my CS 350 class. Intended to work on Raspi 4.0+


# 📁 CS 350 – Embedded Systems Final Project Reflection

**Course:** CS 350 – Emerging Systems Architectures and Technologies  
**Student:** Thomas Cheek  
**Project Title:** Smart Thermostat with Cloud Integration Architecture  

---

## 📌 Selected Artifacts

1. (Thermostat.py) – Python-based embedded control software interfacing with temperature sensors, LEDs, buttons, LCD, and UART output.  
2. (CS350 Analysis Report.pdf) – Hardware architecture analysis and recommendation report for transitioning the prototype to a Wi-Fi-enabled production design.

---

## 📄 Project Overview

The final project focused on developing a smart thermostat prototype that could interface with real hardware components (temperature sensors, LEDs, buttons, LCD) and communicate data via UART. It addressed challenges in writing interface-level software while managing system state and peripheral coordination. In the second phase, I evaluated multiple hardware platforms and proposed a suitable architecture for cloud connectivity, aligning with both business and technical requirements.

---

## ✅ What I Did Well

I implemented a modular and readable control system using Python and GPIO libraries, successfully integrating multithreading for LED fading effects and UART for status reporting. I also demonstrated strong documentation and justification skills in the hardware architecture report, showing the ability to bridge technical design and real-world application needs.

---

## 🧠 Where I Could Improve

I initially underestimated the complexity of synchronizing concurrent hardware operations (e.g., threading with GPIO updates), which led to some instability that required troubleshooting. In future projects, I would dedicate more time to system planning and testing under edge cases.

---

## 🧰 Tools & Resources Added

- `gpiozero` / Adafruit CircuitPython libraries  
- UART and I2C diagnostic techniques  
- Microchip datasheets and IoT cloud integration documentation  

These resources are now part of my embedded development toolkit and will be useful in future hardware-software integration work.

---

## 🔄 Transferable Skills

- Writing embedded interface code and managing physical device state  
- Debugging real-time hardware behavior  
- Evaluating hardware architectures based on performance and integration needs  
- Communicating complex technical decisions clearly in written form  

---

## 🧩 Maintainability, Readability, and Adaptability

I emphasized modular function design, used descriptive naming conventions, and separated logic for hardware setup, state control, and display management. Commenting and docstrings were applied throughout. This structure allows for easy expansion—such as integrating Wi-Fi or cloud features—without disrupting existing functionality.
