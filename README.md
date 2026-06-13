# Single ESC for BLDC Motor

A custom single-channel ESC (Electronic Speed Controller) for BLDC motors. I want to programm and test the esc before modifying it into a 4in1 esc i can use for flying a drone.

## Overview

This repository contains the KiCad schematic and PCB layout for a single-channel ESC. The design is based on the DRV8353 gate driver and BSC010N04LSI MOSFETs, controlled by an STM32G431 microcontroller. It includes a buck converter for onboard power regulation, MOSFET-based battery backflow protection, and BEMF sensing for sensorless motor control.

## Repository Structure

- `SingleEsc.kicad_pro`   — KiCad project file
- `SingleEsc.kicad_sch`   — Schematic
- `SingleEsc.kicad_pcb`   — PCB layout
- `footprints/`           — Custom footprint library
- `myBibs/`               — Custom schematic library
- `GerberESC_V1/`         — Gerber files for manufacturing

## Bill of Materials

A BOM with all components for buying on Digikey is available in the project files. Some parts need to be bought elsewhere for example the XT60 connector.

## AI Usage

AI was used for helping with a basic idea for a layout, learning about components and an idea of where to buy parts.
