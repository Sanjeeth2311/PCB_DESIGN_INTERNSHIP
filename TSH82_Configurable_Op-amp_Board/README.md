# TSH82_Configurable_Op-amp_Board

![Status: Internship Project](https://img.shields.io/badge/Status-Internship%20Project-blue)
![Tool: KiCad](https://img.shields.io/badge/Tool-KiCad-brightgreen)
![Layers: 2](https://img.shields.io/badge/Layers-2%20Layer-orange)

## Project Overview

This is a configurable dual operational amplifier board design.

**Simple Explanation:**  
This board features the TSH82, a high-speed dual op-amp from STMicroelectronics, in a flexible breakout configuration. It allows easy experimentation with different op-amp circuits such as inverting/non-inverting amplifiers, filters, comparators, instrumentation amplifiers, or differential drivers. Jumpers and resistors/capacitors placeholders make it highly configurable for various gain and bandwidth settings.

- **Layer Count:** 2-layer PCB
- **Key Components:** TSH82 dual op-amp, power supply decoupling capacitors, configuration resistors/capacitors, pin headers for inputs/outputs/power, optional feedback components
- **Features:** Dual independent channels, configurable gain and feedback via jumpers or solder bridges, ±5V or single-supply operation support, easy access to all pins

This project focused on practicing analog layout techniques, proper power decoupling, signal integrity for high-speed op-amps, component placement, and manufacturing standards.

## Images

- **Schematic Editor**: [Schematic_Editor.png](Captures/Schematic_Editor.png)
- **PCB Editor**: [PCB_Editor - Top View.png](Captures/PCB_Editor_F_CU.png)
- **PCB Editor**: [PCB_Editor - Bottom View.png](Captures/PCB_Editor_B_CU.png)
- **3D View 1**: [3D_Viewer_1.png](Captures/3D_Viewer_1.png)
- **3D View 2**: [3D_Viewer_2.png](Captures/3D_Viewer_2.png)
- **BOM**: [BOM.png](Captures/BOM.png)

## Project Files

The repository contains the full KiCad project:

- **Gerbers**: [Gerbers](Gerbers)

## Notes

- Design follows TSH82 datasheet recommendations for layout, decoupling, and thermal considerations.
- All DRC (Design Rule Check) and ERC (Electrical Rule Check) passed with no errors.
- Optimized for low-cost 2-layer PCB fabrication.

This project helped me improve my skills in PCB layout techniques, design standards, and manufacturing constraints.

Feedback is always welcome!