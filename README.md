# Mach-Zehnder Interferometer (MZI) – Optical Communication Simulator

## Overview

This repository contains:

- An interactive HTML5 simulator of a Mach-Zehnder Interferometer (MZI)
- A mathematically rigorous technical report in Markdown
- A complete implementation of digital transmission using phase modulation

Developed for the postgraduate course in Quantum Communication – SENAI CIMATEC.

---

## Features

### 1. Interactive MZI Simulation

- 50:50 beam splitters
- Phase control (φ ∈ [0°, 360°])
- Real-time intensity visualization
- Energy conservation validation
- Animated optical wave propagation

Implements:

I₁ = I₀ sin²(φ/2)  
I₂ = I₀ cos²(φ/2)

---

### 2. Digital Transmission Module

- 5-bit fixed-length encoding dictionary
- Text normalization
- Bit count computation
- Transmission time estimation
- Based on OOK-NRZ modulation

Assumed system parameters:

- λ = 1550 nm
- Modulator bandwidth = 40 GHz
- Estimated bitrate ≈ 28 Gbps

---

### 3. Transmission Limits Analysis

- Shannon capacity
- Nonlinear Kerr effects
- Fiber attenuation (0.18 dB/km)
- EDFA noise accumulation
- Intercontinental fiber loss modeling

---

## How to Run

Simply open:

