# Serial-Basic-CH340C-and-USBC

![Status: Internship Project](https://img.shields.io/badge/Status-Internship%20Project-blue)
![Tool: KiCad](https://img.shields.io/badge/Tool-KiCad-brightgreen)
![Layers: 2](https://img.shields.io/badge/Layers-2%20Layer-orange)

## Project Overview

This is a simple USB-to-Serial converter board designed during my 6-month PCB design internship.

**Simple Explanation:**  
This board uses the CH340C USB-to-UART chip to convert USB signals (via USB-C connector) to standard serial UART signals (TX, RX, GND, etc.). It is ideal for programming microcontrollers (such as Arduino or ESP32) or debugging devices that use serial communication. The design is compact, easy to manufacture, and follows best practices for routing and component placement.

- **Layer Count:** 2-layer PCB
- **Key Components:** CH340C IC, USB-C connector, 12MHz crystal, decoupling capacitors, resistors, pin headers
- **Features:** Serial breakout pins, TX/RX activity LEDs, DTR support for auto-reset

This project focused on practicing component placement, signal routing, power distribution, and manufacturing standards.

## Visuals

### Schematic
![Schematic](Schematic_Editor.png)

### PCB Layout
![PCB Layout - Top Layer](PCB_Editor_F_Cu.png)
![PCB Layout - Bottom Layer](PCB_Editor_B_Cu.png)

### 3D View
![3D View 1](3D_Viewer_1.png)
![3D View 2](3D_Viewer_2.png)
![3D View 3](3D_Viewer_3.png)

### Bill of Materials (BOM)
![BOM](BOM.png)

## Project Files

The repository contains the full KiCad project:

- `/Gerbers/` 
s
## Notes

- Design follows CH340C datasheet recommendations and USB-C configuration guidelines.
- All DRC (Design Rule Check) and ERC (Electrical Rule Check) passed with no errors.
- Optimized for low-cost 2-layer PCB fabrication.

This project helped me improve my skills in PCB layout techniques, design standards, and manufacturing constraints.

Feedback is always welcome!
