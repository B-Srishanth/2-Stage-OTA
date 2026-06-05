# 2-Stage OTA Design using LTspice

## Overview

This project presents the design and simulation of a two-stage Operational Transconductance Amplifier (OTA) using LTspice. The design was developed by calculating transistor dimensions and bias conditions, followed by open-loop and closed-loop simulations to verify gain, stability, and transient performance.

## Project Files

```
2-stage-OTA/
│
├── Handcalculations.pdf
├── LTspice_screenshots.pdf
│
├── 2 stage OTA open loop design.asc
├── 2 stage ota closed loop design for dc gain 2.asc
├── 2 stage ota step response design.asc
```

## Design Parameters

| Parameter | Value |
|------------|---------|
| Compensation Capacitor (Cc) | 10 pF |
| Compensation Resistor (Rz) | 2 kΩ |
| Load Capacitor (Cl) | 10 pF |

## Open-Loop Performance

- Low-frequency gain: **64.59 dB**
- Phase margin: **58.25°**
- Frequency response verified using AC analysis.

## Closed-Loop Performance

- Closed-loop gain: **≈ 2 V/V**
- Phase margin: **78.89°**
- Stable transient response with low overshoot.

## Simulations Performed

- Open-loop frequency response
- Closed-loop frequency response
- Closed-loop step response

## Tools Used

- LTspice
- CMOS transistor models
- Analog IC Design concepts

## Results

The designed two-stage OTA achieves high open-loop gain, adequate phase margin, and stable closed-loop operation. Simulation results closely match the theoretical calculations.

## Author

**B.Srishanth**  
B.Tech, Electronics and Communication Engineering  
Indian Institute of Technology Guwahati