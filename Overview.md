# EE-1004 Lab Project – Fall 2025
## Construction of a Common Source Amplifier

### Submitted By
- Muhammad Saad Khan — 24I-6550
- Abdul Hadi — 24I-6538

### Institution
National University of Computer and Emerging Sciences (FAST-NUCES), Islamabad

---

# Project Overview
This project focuses on the design and implementation of a single-stage Common Source Amplifier using a BS170 MOSFET. The amplifier was designed according to the given specifications and implemented on a custom fabricated 3 inch × 3 inch PCB.

The project included:
- Circuit calculations and biasing design
- PCB layout and fabrication
- Etching and drilling
- Component soldering and assembly
- Simulation and practical testing

The final amplifier successfully amplified a low-amplitude sinusoidal signal and produced the expected 180° phase shift.

---

# Objectives
- Design a MOSFET-based Common Source Amplifier
- Achieve stable voltage gain
- Compare simulated and practical results
- Gain hands-on experience with PCB fabrication and analog electronics

---

# Components Used

| Component | Value |
|------------|------------|
| MOSFET | BS170 |
| Fixed Resistor | 100 kΩ |
| Variable Resistor (Potentiometer) | 100 kΩ |
| Drain Resistor (RD) | 15 kΩ |
| Source Resistor (RS) | 15 kΩ |
| Input Coupling Capacitor | 33 nF |
| Output Coupling Capacitor | 100 nF |
| Source Bypass Capacitor | 1 µF |
| DC Supply | 18V |

---

# PCB Materials
- Single-sided 3×3 inch PCB
- Permanent marker
- Sand paper
- Ferric chloride solution
- Cotton and nail polish remover

---

# Tools Used
- Soldering iron and solder wire
- PCB drill machine
- Oscilloscope
- Multimeter
- Function generator

---

# Circuit Description
The circuit operates as a Common Source MOSFET amplifier where:
- The input signal is applied at the gate terminal.
- The MOSFET amplifies the signal using proper biasing.
- The amplified output is obtained from the drain terminal.
- Coupling capacitors isolate DC components.
- The bypass capacitor improves voltage gain.

The amplifier was tested using:
- Input Signal: 24 mV peak-to-peak sine wave
- Frequency: 50 Hz
- Supply Voltage: 18V DC

---

# Simulation Results

| Parameter | Value |
|------------|------------|
| Vg | 9 V |
| Vd | 12.9 V |
| Vs | 6.32 V |
| Vgs | 1.99 V |
| Vds | 5.7 V |
| Id | 0.64 mA |
| Voltage Gain (Av) | 34 V/V |

---

# Practical Results

| Parameter | Value |
|------------|------------|
| Vg | 8.12 V |
| Vd | 12.67 V |
| Vs | 6.03 V |
| Vgs | 2.4 V |
| Vds | 5.2 V |
| Id | 0.59 mA |

---

# Observations
- Practical results closely matched simulation values.
- Stable voltage amplification was achieved.
- Expected 180° phase shift was observed.
- Signal quality improved after bias adjustment and fine tuning.

---

# Conclusion
The Common Source Amplifier was successfully designed, fabricated, and tested. The amplifier achieved a voltage gain of approximately 34 V/V and satisfied the required project specifications. The project provided practical experience in analog circuit design, PCB fabrication, hardware testing, and MOSFET amplifier analysis.

---

# Project Images
Add the following images here:
- Circuit schematic
- PCB layout
- Fabricated PCB
- Final assembled circuit
- Oscilloscope output waveform

---

# Authors
Muhammad Saad Khan  
Abdul Hadi

FAST-NUCES Islamabad
