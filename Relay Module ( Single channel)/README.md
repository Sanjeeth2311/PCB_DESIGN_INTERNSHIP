# Single-Channel-Relay-Module

![Status: Internship Project](https://img.shields.io/badge/Status-Internship%20Project-blue)
![Tool: KiCad](https://img.shields.io/badge/Tool-KiCad-brightgreen)
![Layers: 2](https://img.shields.io/badge/Layers-2%20Layer-orange)

## Project Overview

This is a single-channel relay module board design.

**Simple Explanation:**  
This board allows a low-voltage microcontroller (like Arduino, ESP32, or Raspberry Pi) to safely control high-voltage AC or DC loads (e.g., lights, fans, appliances) using a 5V relay. The relay provides electrical isolation between the control side and the load side. Optocoupler isolation protects the microcontroller, and onboard LED indicators show relay status.

- **Layer Count:** 2-layer PCB
- **Features:** Control input (active low/high configurable), relay status LED, high-voltage screw terminals, isolation between control and load

This project focused on practicing component placement, signal routing, power distribution, high-voltage clearance rules, and manufacturing standards.

## Images

- **Schematic Editor**: [Schematic_Editor.png](Captures/Schematic_Editor.png)
- **PCB Editor**: [PCB_Editor.png](Captures/PCB_Editor.png)
- **3D View 1**: [3D_Viewer_1.png](Captures/3D_Viewer_1.png)
- **3D View 2**: [3D_Viewer_2.png](Captures/3D_Viewer_2.png)
- **BOM**: [BOM.png](Captures/BOM.png)

## Project Files

The repository contains the full KiCad project:

- **Gerbers**: [Gerbers](Gerbers)

## Notes

- Design follows standard relay module practices with proper creepage and clearance for safety.
- All DRC (Design Rule Check) and ERC (Electrical Rule Check) passed with no errors.
- Optimized for low-cost 2-layer PCB fabrication.

This project helped me improve my skills in PCB layout techniques, design standards, and manufacturing constraints.

Feedback is always welcome!