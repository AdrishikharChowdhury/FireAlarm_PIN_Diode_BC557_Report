# Fire Alarm using Flame Sensor and BC557 Transistor

A cost-effective fire alarm system that detects flames using a PIN diode type flame sensor and triggers visual and audible alerts through a BC557 transistor.

## Overview

This project implements a fire alarm system using:
- **Flame Sensor (PIN Diode type)** - Detects flame by sensing infrared light emitted by flames
- **BC557 Transistor (PNP)** - Acts as a switch to amplify the sensor signal
- **Blue LED** - Visual indication when fire is detected
- **Buzzer** - Audible alert when fire is detected
- **Resistor (1kΩ)** - Current limiting
- **Battery (5V-9V)** - Power supply

## Block Diagram

```
Battery (5V-9V) → Flame Sensor → BC557 Transistor → LED & Buzzer
```

## Circuit Diagrams

- **Practical Circuit**: `Circuit Diagram.png`
- **Simulation Circuit**: `Software Circuit Diagram.png`
- **Flowchart**: `flowchart.png`

## Project Workflow

1. Research & Conceptualization
2. Components Selection
3. Software Simulation (TinkerCAD)
4. Practical Implementation
5. Calibration & Adjustment
6. Testing & Results
7. Data Collection
8. Documentation & Reporting

## Results

- **Average Detection Distance**: ~15 cm
- **Average Sensitivity**: 0.01344 S/cm
- Detection Reliability Index (DRI) tested at various distances

Graphs:
- `DRI vs Distance graph.png`
- `Average Time vs Distance graph.png`

## Project Team

- Sounak Mal (12200323050)
- Jagannath Maji (12200323024)
- Pradip Mandal (12200323031)
- Ritankar Mandal (12200323037)

## Future Scope

- Integration with smart home systems
- Use of advanced sensors (smoke, gas, temperature)
- Wireless communication (Wi-Fi/Bluetooth)
- Energy efficiency improvements
- Machine learning for fire detection

## Files

| File | Description |
|------|-------------|
| `Circuit Diagram.png` | Practical circuit diagram |
| `Software Circuit Diagram.png` | TinkerCAD simulation |
| `flowchart.png` | Operation flowchart |
| `Report/main.tex` | LaTeX project report |
| `Report/main.pdf` | PDF report |
| `CSV/` | Experimental data |
| `Excel/` | Data analysis files |
