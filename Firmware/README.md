
## Description
Embedded firmware for measuring voltage and current with high precision.

## Features
- ADC sampling (2kS/s)
- UART data transmission
- SSD1306 OLED display support

## Display Drivers
- SSD1306 OLED (I2C)
- Files located in `/Display_Drivers`

## How to Run
1. Open project in STM32CubeIDE
2. Build project
3. Flash to STM32F401CCU6 board

## Notes
- Ensure correct ADC calibration
- Verify I2C connection for OLED
- Verify UART connection for HC-05 Bluetooth module

##
STM32CubeIDE can be download using below Link: 
https://www.st.com/en/development-tools/stm32cubeide.html
