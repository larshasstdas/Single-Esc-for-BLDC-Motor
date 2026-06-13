# Single ESC for BLDC Motor

A custom single-channel ESC (Electronic Speed Controller) for BLDC motors, designed as part of the [SelfmadeDrone](https://github.com/larshasstdas/SelfmadeDrone) project.

## Overview

This repository contains the KiCad schematic and PCB layout for a single-channel ESC. The design is based on the DRV8353 gate driver and BSC010N04LSI MOSFETs, controlled by an STM32 microcontroller. It includes a buck converter for onboard power regulation, MOSFET-based battery backflow protection, and BEMF sensing for sensorless motor control.

## Repository Structure

- `SingleEsc.kicad_pro` — KiCad project file
- `SingleEsc.kicad_sch` — Schematic
- `SingleEsc.kicad_pcb` — PCB layout
- `footprints/` — Custom footprint library
- `GerberESC_V1/` — Gerber files for manufacturing

## Bill of Materials

A full BOM with all components, values, and footprints is available in the roject files. The file was generated with AI to directly list part numbers. Some of these parts might not be available in your shops of choice, but they can be swapped with similiar parts.
