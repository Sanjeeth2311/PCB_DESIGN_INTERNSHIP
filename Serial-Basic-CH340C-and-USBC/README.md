```markdown
# Serial-Basic-CH340C-and-USBC

![Status: Internship Project](https://img.shields.io/badge/Status-Internship%20Project-blue)
![Tool: KiCad](https://img.shields.io/badge/Tool-KiCad-brightgreen)
![Layers: 2](https://img.shields.io/badge/Layers-2%20Layer-orange)

## Project Overview

This is a simple USB-to-Serial converter board design.

**Simple Explanation:**  
This board uses the CH340C USB-to-UART chip to convert USB signals (from a USB-C connector) to standard serial UART signals (TX, RX, GND, etc.). It is perfect for programming microcontrollers (like Arduino, ESP32) or debugging devices that communicate over serial. The design is compact, beginner-friendly, and follows good PCB layout practices for clean routing and manufacturability.

- **Layer Count:** 2-layer PCB
- **Key Components:** CH340C IC, USB-C connector, 12MHz crystal, decoupling capacitors, resistors, pin headers
- **Features:** Basic serial breakout with TX/RX LEDs (if added), DTR for auto-reset support

This project was part of my practice focusing on component placement, signal routing, power distribution, and adherence to manufacturing standards.

## Visuals

### Schematic
![Schematic](Schematic_Editor.png)

### PCB Layout (Top View)
![PCB Layout](PCB_Editor_F_Cu.png)
![PCB Layout](PCB_Editor_B_Cu.png)

### 3D View
![3D View 1](3D_Viewer_1.png)
![3D View 2](3D_Viewer_2.png)
![3D View 3](3D_Viewer_3.png)

### Bill of Materials (BOM)
![BOM](BOM.png)

## Project Files

The repository contains the full KiCad project:

- Gerber files

## Notes

- Design strictly follows CH340C datasheet recommendations and USB-C standards.
- All DRC and ERC checks passed with no errors.
- Optimized for low-cost 2-layer fabrication.

This project helped strengthen my skills in layout techniques, design rules, and manufacturing constraints.

Feedback is always welcome!