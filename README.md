# Design and Analysis of Two-Stage Operational Amplifier Using 65nm CMOS

## Overview

This project presents the design and analysis of a two-stage CMOS operational amplifier using 65nm technology in Cadence Virtuoso.

The work focuses on:

- Common Source Amplifier Design
- Common Drain (Source Follower) Design
- Differential Amplifier Design
- Two-Stage Operational Amplifier Integration
- AC and Transient Performance Analysis

---

## Block Diagram

![Architecture](images/architecture.png)

---

## Design Flow

### 1. Common Source Amplifier

Purpose:
- High voltage gain stage
- First study of amplification behavior

Results:
- Gain ≈ 18 dB

![Common Source](schematics/Common_Source.png)

---

### 2. Common Drain Amplifier

Purpose:
- Buffer stage
- Low output impedance

Results:
- Near unity gain
- Improved load driving capability

![Common Drain](schematics/Common_Drain.png)

---

### 3. Differential Amplifier

Purpose:
- High common-mode noise rejection
- Differential signal amplification

Components:
- Current Mirror
- Differential Pair
- Active Load

![Differential Amplifier](schematics/Differential_Amplifier.png)

---

### 4. Two-Stage Operational Amplifier

Architecture:

Current Mirror
→ Differential Pair
→ Common Source Stage
→ Compensation Capacitor

![Two Stage OpAmp](schematics/Two_Stage_OpAmp.png)

---

## Simulation Results

### Transient Response

![Transient](images/transient_response.png)

### AC Response

![AC Response](images/bode_plot.png)

---

## Performance Summary

| Parameter | Value |
|------------|---------|
| Gain | 35 dB |
| Unity Gain Bandwidth | 2.72 GHz |
| Gain Margin | 9.54 dB |
| Phase Margin | 71° |

---

## Tools Used

- Cadence Virtuoso
- 65nm CMOS PDK
- Spectre Simulator

---

## Applications

- Analog Front-End Circuits
- Data Converters
- Sensor Interfaces
- RF Systems
- Mixed-Signal ICs

---

## Author

Serina Sakhare

B.Tech Electronics & Communication Engineering

Manipal Institute of Technology

Internship Project – Space Applications Centre (ISRO)
