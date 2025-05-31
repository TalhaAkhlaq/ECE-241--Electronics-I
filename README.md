# Electronics I  
This repository contains coursework and projects from the ECE-241: Electronics I course, which introduces the principles of semiconductor device physics, diode and transistor behavior, and amplifier design.

## Course Overview  
The course covers the following key concepts:

- **Semiconductor Physics**: Energy band theory, carrier distributions, drift and diffusion transport.
- **PN Junction Devices**: Structure, I-V characteristics, junction capacitance, and switching behavior.
- **Diode Circuits**: Rectifiers, clippers, clampers, and voltage regulators.
- **Bipolar Junction Transistors (BJTs)**: Modes of operation, DC biasing, small-signal models.
- **CMOS Transistors**: Threshold voltage, I-V characteristics, and region classification.
- **Amplifier Design**: Common emitter/source configurations, small-signal gain, input/output impedance.
- **AC and DC Analysis**: Analytical solutions and simulation of signal response.
- **EDA Tools**: Use of Cadence Virtuoso and Spectre on a virtualized environment.

## Project Description and Overview  

### Final Project: Common Source Amplifier  
The final project involved the design, biasing, simulation, and analysis of a **Common Source Amplifier** using CMOS transistors. Implemented in **Cadence Virtuoso**, this amplifier demonstrates voltage gain through phase-inverted output and operates in the saturation region for high fidelity.

#### Key Features:
- **Biasing Network**: Establishes correct Q-point using resistive divider and current mirror reference.
- **Load Design**: Passive resistor and active load topologies simulated and compared.
- **AC Response**: Frequency response and gain measured using Spectre simulations.
- **Output Characteristics**: Voltage swing, linearity, and gain-bandwidth product evaluated.

#### Tools and Environment:
- **Software**: Cadence Virtuoso & Spectre (Academic Edition)
- **Access**: Installed on a remote-access **Linux virtual machine** provided by the university IT services.
- **Process**:
  1. Connect via **SSH** to the virtual machine
  2. Launch Cadence environment
  3. Use Virtuoso's Schematic Editor to build circuit
  4. Run DC and AC simulations using Spectre from ADE (Analog Design Environment).
  5. Save waveforms and extract gain, frequency response, and output swing metrics.

#### Schematic and simulation outputs can be found [here](https://github.com/TalhaAkhlaq/ECE-241-Electronics-I/tree/main/Final%20Project).
---
## Copyright & Licensing

Copyright (C) 2024 Talha Akhlaq <talhaakhlaq1@gmail.com>

Distributed under the MIT License. See LICENSE for details.
##

For more information on my projects and other academic work, please visit my [GitHub profile](https://github.com/TalhaAkhlaq).
