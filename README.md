# Multi-Band PLL-Based RF Signal Generation System

This project presents the design and implementation of a multi-band RF signal generation and filtering system based on a PLL-VCO architecture using the ADF4351.

## System Overview

The system generates RF signals at:
- 0.6 GHz
- 0.9 GHz
- 1.2 GHz

Signals are routed through switchable LC band-pass filters using RF switches to achieve a clean and selectable output.

## Key Components

- ADF4351 PLL-VCO (25 MHz reference)
- MCU (SPI + GPIO control)
- Dual SP3T RF switches
- LC Band-Pass Filters (~200 MHz bandwidth)

## Design Highlights

- RF simulation using AWR Microwave Office  
- Harmonic suppression (up to ~70 dB)  
- 4-layer PCB design (KiCad)  
- 50Ω controlled impedance RF traces  
- RF and digital separation  
- Via stitching for grounding  

## Performance

- Insertion loss: ~2.5–3.5 dB  
- Harmonic suppression: up to ~70 dB  

## Skills

- RF system design  
- Filter design  
- PLL frequency synthesis  
- PCB design  
- Embedded systems  

## Author

Hasan Emre Aydemir  
