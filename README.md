# LCD-Smartie

This repository contains example codes, configuration files, and schematics for using **LCD Smartie** with various Arduino-compatible LCD displays, including popular sizes like **16x2**, **20x4**, and others. The code allows the LCD display to interface with the LCD Smartie software, enabling dynamic updates, such as custom text, animations, and live data visualization.

---

## Features
- Supports **16x2**, **20x4**, and similar LCD sizes.
- Compatible with **HD44780-based LCD controllers**.
- Detailed instructions for connecting the LCD to an Arduino.
- Pre-configured plugin examples (e.g., **LCDT.dll**) for seamless integration with LCD Smartie.

---

## How to Use

### 1. **Hardware Requirements**

- An Arduino-compatible microcontroller (e.g., Arduino Uno, Mega).
- LCD display (e.g., 16x2 or 20x4) with HD44780 controller.
- Potentiometer or rezistors (for adjusting LCD contrast).
- Connection wires and a breadboard.
- Download LCD Smartie program for Windows: https://sourceforge.net/projects/lcdsmartie/files/lcdsmartie/5.4.2.92%2B%2B/LCD_Smartie_v5.4.2.92%2B%2B.zip/download
  
### 2. **Code**
Find in this repository code for your LCD Dsiplay
Currently supporting:
- 16x2
- 20x4
- more in near future!

### 3. **Connections**
Refer to the schematic diagram for connecting the LCD display to the Arduino. Below is an example for a **classic LCD**:

| LCD Pin | Arduino Pin | Description                   |
|---------|-------------|-------------------------------|
| RS      | 12          | Register Select              |
| E       | 11          | Enable                       |
| D4      | 5           | Data line                    |
| D5      | 4           | Data line                    |
| D6      | 3           | Data line                    |
| D7      | 2           | Data line                    |
| VSS     | GND         | Ground                       |
| VDD     | 5V          | Power supply                 |
| VO      | Potentiometer | Contrast adjustment          |
| RW      | GND         | Write mode (ground for write) |
| A       | 5V          | Backlight power              |
| K       | GND         | Backlight ground             |

**Schematic:**
- Will work with 16x4, 20x4 etc

![Forge Logo](img/uno.png)
---

### 3. **Software Setup**
1. Clone this repository:
   ```bash
   git clone https://github.com/WyerFrameZ/LCD-Smartie.git

