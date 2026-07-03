# ESP32 All-Sensor Board (4-Layer PCB Design)

## 📖 Overview
This repository contains the design files for a custom 4-layer PCB integrating the ESP32 microcontroller with multiple sensors and supporting circuits.  
The board is designed as a compact all-in-one sensor platform for IoT and embedded system experiments. It includes sensor interfaces, amplifier circuits, and a regulated power section, making it suitable for real-world prototyping and academic projects.

---

## ⚙️ Features
- **ESP32 Microcontroller**
  - Dual-core processor with Wi-Fi + Bluetooth
  - GPIO breakout pins for external modules
- **Integrated Sensors**
  - BMP90 sensor for pressure and temperature measurement
  - Humidity sensor interface for environmental monitoring
- **Amplifier System**
  - Signal conditioning stage for sensor outputs
  - Designed for clean analog-to-digital conversion
- **Power Section**
  - LDO-based regulation for 3.3V and 5V rails
  - Separate copper planes for power and ground
  - Decoupling capacitors for noise reduction
- **PCB Design**
  - 4-layer stack-up for optimized routing
  - Dedicated copper planes for stability
  - Compact layout with clear separation of analog and digital sections

---

## 📂 Repository Contents
- **/schematics** → Circuit schematic files (`.sch`, `.pdf`)
- **/pcb_layout** → PCB design files (`.kicad_pcb`, EasyEDA exports)
- **/gerber** → Gerber files for fabrication
- **/images** → PCB screenshots (top layer, bottom layer, 3D view)
- **README.md** → Project description and usage details

---

## 🖼️ PCB Views
![Top Layer](images/top_layer.png)
![Bottom Layer](images/bottom_layer.png)
![3D View](images/3d_view.png)

---

## 🚀 Tools Used
- **EasyEDA** → schematic & PCB design
- **KiCad** → verification and cross-checking
- **Standard PCB workflow** → Gerber export for manufacturing

---

## 🎯 Applications
- IoT sensor fusion projects
- Environmental monitoring (temperature, humidity, pressure)
- Embedded system prototyping with ESP32
- Signal conditioning experiments with amplifier circuits
- Academic learning for PCB design and hardware integration

---

## 🛠 How to Use
1. Clone this repository  
2. Open schematic files in EasyEDA/KiCad  
3. Review PCB layout and modify if needed  
4. Use Gerber files for fabrication  
5. Assemble components and test sensor outputs with ESP32 firmware  

---

## 📌 Future Improvements
- Add more sensors (gas, accelerometer, gyroscope)  
- Improve amplifier stage for higher accuracy  
- Add USB-C power input and charging circuit  
- Integrate OLED display for real-time sensor data  

---

## 📜 License
This project is licensed under the **MIT License** – feel free to use, modify, and share with proper credit.
