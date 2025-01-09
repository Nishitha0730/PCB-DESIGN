# STM32 PCB Design

## Overview

This is a 4-layer PCB design project created using Altium Designer 24. The project includes the following components:

- STM32F4 Microcontroller
- MPU-6050 
- USB Connector
- LDO Regulator (5V to 3.3V conversion)

The project is based on a hierarchical schematic design, ensuring modularity and ease of debugging. Below are the schematic diagrams, PCB layers, and a 3D view of the final design.

---

## Hierarchical Schematic Diagram

This diagram outlines the overall structure of the circuit, incorporating key components such as the STM32F4 microcontroller, MPU-6050, USB connector, and LDO regulator.

![Hierarchical Schematic Diagram](https://github.com/Nishitha0730/PCB-DESIGN/blob/main/Heiratical%20Shematic%20Diagram.png)

---

## Component Schematics

### MPU-6050 Schematic Diagram



![MPU-6050 Schematic Diagram](https://github.com/Nishitha0730/PCB-DESIGN/blob/main/MPU%206050.png)

### USB Connector & LDO Regulator

This section of the schematic shows the USB connector for data and power transfer and the LDO regulator for stepping down 5V to 3.3V.

![USB Connector & LDO Regulator](https://github.com/Nishitha0730/PCB-DESIGN/blob/main/USB%20Connector%20and%20LDO%20Regulator.png)

---

## PCB Design Layers

### Top Layer

The top layer of the PCB includes critical signal routing for high-speed signals and major components.

![Top Layer](https://github.com/Nishitha0730/PCB-DESIGN/blob/main/Top%20Layer.png)

### Bottom Layer

The bottom layer serves for power distribution and grounding, ensuring proper signal integrity.

![Bottom Layer](https://github.com/Nishitha0730/PCB-DESIGN/blob/main/Bottom%20Layer.png)

### 3D View

The 3D view provides a visual representation of the assembled PCB, showing component placement and layer alignment.

![3D View](https://github.com/Nishitha0730/PCB-DESIGN/blob/main/3D%20View.png)

---

## Tools & Resources

This PCB was designed by following the tutorial:
**[STM32 PCB Design - Complete Walkthrough - Altium Designer & JLCPCB - Phil's Lab #41](https://www.youtube.com/watch?v=examplelink)**

---

## Future Improvements

Creating a detailed README like this for GitHub can enhance documentation for projects and aid in securing internships by showcasing your technical skills. For further improvement:

- Include detailed descriptions of each schematic section.
- Provide a Bill of Materials (BOM) for easier replication.
- Add links to additional resources or references for learning.

---

Thank you for viewing this project! Feel free to explore the repository and provide feedback.

