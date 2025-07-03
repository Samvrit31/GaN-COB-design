# GaN-COB-design


## Overview

As part of an internship at Semiconductor Laboratory (SCL), Mohali, this project focused on transforming a bare GaN die into a functional IC module using a TO-220 style COB PCB design. The aim was to create a reliable, and thermally efficient layout suitable for high-voltage, high-current GaN applications.

## Design Workflow

- **Schematic and Layout Design**:  
  The PCB layout was created in **OrCAD**, covering the entire signal path from the die’s wire bond pads to the outer TO-220 style pins. The board uses an **FR4 substrate with 2oz copper** to handle high current levels efficiently.
  
- **Key Features**:
  - Complete bond pad to pin routing
  - Force-sense wire bonds for accurate voltage sensing
  - Plated Through Holes (PTH) and thermal vias for heat distribution
  - Track width and spacing manually calculated for 10A continuous current

- **3D Modeling**:  
  **KiCad** was used to create a 3D model of the PCB and packaging, ensuring accurate mechanical alignment of all layers — die, bond wires, pad layout, and outer pins.

## Thermal Analysis

- Thermal performance was evaluated using **SimScale**, a cloud-based multiphysics simulation tool.
- Simulations focused on passive heat dissipation using internal copper layers, vias, and layout optimization — without any external heat sink.

## Tools Used

- **OrCAD** – Schematic and PCB layout design
- **KiCad** – 3D modeling and visualization
- **SimScale** – Thermal simulation

## Outcome

- Final layout and 3D models are ready for fabrication.
- Demonstrated practical integration of GaN HEMT packaging and thermal design in compact form.

