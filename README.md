# Multi-Band PLL-Based RF Signal Generation System

Final-year Electronics and Communication Engineering student project focused on multi-band RF signal generation and filtering using a PLL-VCO architecture.

## System Overview

The system generates RF signals at:
- 0.6 GHz
- 0.9 GHz
- 1.2 GHz

Signals are routed through switchable LC band-pass filters via RF switches to achieve a clean and selectable output.

## Key Components

- ADF4351 PLL-VCO (25 MHz reference)
- MCU (SPI & GPIO control)
- Dual SP3T RF switches
- LC Band-Pass Filters (~200 MHz bandwidth)

## Design Highlights

- RF simulation (AWR Microwave Office)  
- Harmonic suppression up to ~70 dB  
- 4-layer PCB design (KiCad)  
- 50Ω controlled impedance RF traces  
- RF/digital isolation and via stitching  

## Performance

- Insertion loss: ~2.5–3.5 dB  
- Harmonic suppression: up to ~70 dB  

## Skills

- RF system design  
- Filter design  
- PLL frequency synthesis  
- PCB design  
- Embedded systems  

## Report

📄 [Download Project Report](rf-pll-report.pdf)

## Author

Hasan Emre Aydemir  
Open to entry-level RF / Embedded Systems opportunities
