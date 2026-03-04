# Two-Stage-CMOS-OpAmp-90nm-in-Cadence-Virtuoso
## Overview
This project presents the **pre-layout design and simulation** of a **two-stage CMOS operational amplifier** in **90nm CMOS** using **Cadence Virtuoso**.  
The design achieves **62.9 dB DC gain**, **25.1 MHz GBW**, and **77° phase margin** with a **1 pF load**.  
A **Monte Carlo analysis (200 runs)** was also performed to evaluate robustness under process variation.

## Key Results
- **DC Gain:** 62.9 dB  
- **GBW:** 25.1 MHz  
- **Phase Margin:** 77°  
- **DC Offset:** 657.82 µV  
- **CMRR:** 75.197 dB  
- **PSRR:** 69.1 dB  
- **Slew Rate:** 16.27 V/µs  

## Architecture
The op-amp uses a classical **two-stage CMOS topology**:
- **NMOS differential input pair**
- **PMOS current mirror active load**
- **NMOS tail current source**
- **Second gain stage**
- **Compensation capacitor**

## Design and Simulation Flow
The following analyses were carried out:
- DC operating point analysis
- AC response analysis
- DC offset analysis
- CMRR analysis
- PSRR analysis
- Slew-rate transient analysis
- Power simulation
- Monte Carlo analysis
