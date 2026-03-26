# Ultra-Precision Current and Voltage Measurement System

## 📌 Overview
This project presents a **high-accuracy embedded measurement system** designed to measure:

- Current: **1µA to 100mA**
- Voltage: **1V to 12V**

The system is built using an **STM32F411 microcontroller** with precision analog front-end circuits and supports **data logging, calibration, and real-time display using an SSD1306 OLED**.

---

## 🚀 Key Features
- Ultra-low current measurement 
- High-resolution voltage sensing
- Real-time OLED display (SSD1306)
- PC-based data logging via UART
- Calibration using Python

---

## 🧩 Project Structure

| Folder | Description |
|------|-------------|
| firmware | STM32 embedded code |
| hardware | Circuit diagrams & schematics |
| calibration | Python calibration scripts |
| images | Project photos |

---

## ⚙️ Hardware Design

The hardware includes:

- Precision shunt resistor 
- Operational amplifier 
- Voltage divider circuit
- STM32 ADC interface
- OLED display interface (I2C)
- Communication protocal (UART)

👉 See `/hardware` for full design files

---

## 💻 Firmware (STM32)

- Developed using **STM32CubeIDE**
- ADC-based measurement system
- UART communication for logging
- SSD1306 OLED display integration

👉 See `/firmware`

---

## 📊 Calibration System

Calibration is performed using Python scripts:

- `voltage_calibration.py`
- `current_calibration.py`

These scripts:
- Reduce measurement error
- Improve accuracy using curve fitting

👉 See `/calibration`

---

## 🖥️ OLED Display (SSD1306)

- Interface: I2C
- Displays:
  - Voltage
  - Current
- Driver included in firmware

---

## 📈 Data Logging

- Serial communication to PC
- Data stored as `.csv`
- Can be analyzed using:
  - Excel
  - MATLAB
  - Python

---

## 📸 System Preview

![Prototype](images/prototype.jpg)

---

## 👥 Team
- Harsha Chathuranga
- Janudi Dissanayake
- Tharunimi Kodithuwakku
- Sadun Magammana
- Asiri Pathirana
- Pramodth Pereara
- Suditha Perera

---

## ⚠️ Limitations
- Noise in low current region
- Temperature drift
- ADC resolution limits

---

## 🔮 Future Improvements
- External high-resolution ADC
- Auto-ranging system
- GUI software for PC

---

## 📄 License
MIT License
