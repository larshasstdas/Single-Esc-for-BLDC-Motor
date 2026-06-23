# Single ESC for BLDC Motor

A custom single-channel ESC (Electronic Speed Controller) for BLDC motors. I want to programm and test the esc before modifying it into a 4in1 esc i can use for flying a drone.

## Overview

This repository contains the KiCad schematic and PCB layout for a single-channel ESC. The design is based on the DRV8353 gate driver and BSC010N04LSI MOSFETs, controlled by an STM32G431 microcontroller. It includes a buck converter for onboard power regulation, MOSFET-based battery backflow protection, and BEMF sensing for sensorless motor control.

## Files

.
├── KiCad_Files/              # KiCad design source
│   ├── SingleEsc.kicad_pro   # KiCad project file
│   ├── SingleEsc.kicad_sch   # Schematic
│   ├── SingleEsc.kicad_pcb   # PCB layout
│   ├── SingleEsc-job.gbrjob  # Gerber job file
│   ├── SingleEsc-all-pos.csv # Component placement export
│   ├── footprints/           # Custom footprint library
│   ├── myBibs/               # Custom schematic symbol library
│   └── fp-lib-table          # Footprint library table
│
├── Gerber&BOM/               # Manufacturing data
│   ├── GerberESC/            # Gerber and drill files
│   ├── DigiKey_ESC_BOM.csv   # Bill of materials (CSV)
│   ├── DigiKey_ESC_BOM.xlsx  # Bill of materials (Excel)
│   ├── ESC_PickAndPlace.csv  # Pick & place (CSV)
│   └── ESC_PickAndPlace.xlsx # Pick & place (Excel)
│
├── Gerber&BOM.zip            # Zipped Gerber, BOM and Pick & Place files
└── README.md

## Bill of Materials

A BOM with all components for buying on Digikey is available in the project files. Some parts need to be bought elsewhere for example the XT60 connector.

## AI Usage

AI was used for helping with a basic idea for a layout, learning about components and an idea of where to buy parts.
