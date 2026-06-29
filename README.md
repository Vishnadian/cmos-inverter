# CMOS Inverter Design using Cadence Virtuoso

## Overview
This project contains the design, simulation, and layout of a standard CMOS Inverter implemented using Cadence Virtuoso. The CMOS Inverter is a fundamental building block in digital VLSI design, consisting of a PMOS pull-up network and an NMOS pull-down network. 

## Tools Used
* **Cadence Virtuoso Schematic Editor**: For drawing the circuit schematic.
* **Cadence Virtuoso Analog Design Environment (ADE)**: For simulating the circuit (DC and Transient Analysis).
* **Cadence Virtuoso Layout Suite**: For physical layout design.
* **Assura / Calibre**: For Design Rule Check (DRC) and Layout Versus Schematic (LVS) verification.

## Design Flow
1. **Schematic Capture**: Creating the PMOS and NMOS schematic with appropriate W/L ratios to ensure symmetric rise and fall times.
2. **Symbol Creation**: Generating a reusable symbol for the inverter for hierarchical design.
3. **Testbench Setup**: Instantiating the inverter symbol, adding VDD and GND pins, and applying a pulse input signal (`vpulse`).
4. **Simulation**: Running Transient and DC response analyses to observe the voltage transfer characteristics (VTC) and calculate propagation delay.
5. **Layout**: Drafting the physical layout of the PMOS and NMOS transistors, connecting the poly gates, routing metal layers, and adding substrate/n-well contacts.
6. **Verification**: Performing DRC to check for physical design rules and LVS to ensure the layout matches the schematic perfectly.

## Project Screenshots

Below are the screenshots capturing various stages of the design, including schematics, simulations, and layouts:

### Schematic & Design 1
![CMOS Inverter Image 1](images/1776707374547.jfif)

### Schematic & Design 2
![CMOS Inverter Image 2](images/1776707379846.jfif)

### Schematic & Design 3
![CMOS Inverter Image 3](images/1776707394075.jfif)

### Simulation & Analysis 4
![CMOS Inverter Image 4](images/1776707412223.jfif)

### Layout & Results 5
![CMOS Inverter Image 5](images/1776707573206.jfif)

---
*Developed as part of a VLSI Custom IC Design flow.*