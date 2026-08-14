# Design and Analysis of CMOS-Based Hybrid Low Noise Amplifier for X-Band Radar Application

## 📌 Project Overview

This project presents the design and analysis of a CMOS-based hybrid Low Noise Amplifier (LNA) operating at 9.5 GHz for X-band radar receiver applications.

The proposed architecture combines single-ended and differential amplifier stages to achieve a suitable balance between gain, noise performance, input matching, stability, and power consumption. The design was implemented using 45 nm CMOS technology and simulated using Cadence Virtuoso and SpectreRF.

## 🎯 Objectives

- Design a CMOS-based LNA for X-band radar applications.
- Operate the amplifier at a target frequency of 9.5 GHz.
- Achieve high power gain with low noise figure.
- Improve input impedance matching.
- Analyze the trade-offs between gain, noise, stability, and power consumption.
- Validate the design using RF circuit simulations.

## 🏗️ Proposed Architecture

The proposed LNA consists of six amplifier stages:

- Two single-ended stages optimized for low-noise performance.
- Four differential gain stages for additional gain, linearity, and isolation.
- Transformer-based inter-stage coupling.
- Input matching and tuned load networks.
- Biasing networks for stable circuit operation.

The transformer coupling provides impedance transformation and single-ended-to-differential signal conversion.

## ⚙️ Design Specifications

| Parameter | Value |
|---|---|
| Technology | 45 nm CMOS |
| Process Design Kit | gpdk045 |
| Operating Frequency | 9.5 GHz |
| Supply Voltage | 1.0 V |
| Source Resistance | 50 Ω |
| Load Resistance | 50 Ω |
| Architecture | Six-stage Hybrid LNA |
| Application | X-band Radar |

## 🛠️ Tools and Technologies

- Cadence Virtuoso
- Cadence Analog Design Environment (ADE)
- SpectreRF
- 45 nm CMOS gpdk045
- RF circuit simulation
- S-parameter analysis
- Noise analysis
- Transient analysis

## 🔬 Simulation and Analysis

The design was evaluated using multiple circuit analyses, including:

1. **Transient Analysis** – to verify the time-domain response of the amplifier.
2. **S-Parameter Analysis** – to evaluate forward gain and input matching.
3. **Noise Analysis** – to determine the noise figure across the operating frequency.
4. **Gain Analysis** – to evaluate the frequency-dependent gain of the amplifier.

## 📊 Key Results

The simulated design achieved approximately:

- **Forward Gain (S21):** 32.04 dB
- **Input Return Loss (S11):** −19.92 dB
- **Noise Figure:** approximately 4.3–4.4 dB
- **Power Consumption:** approximately 12 mW
- **Supply Voltage:** 1.0 V
- **3 dB Bandwidth:** approximately 8.7–10.2 GHz

These results demonstrate the suitability of the proposed hybrid LNA for X-band receiver front-end applications.

## 👩‍💻 My Role

Contributed to the circuit-level design, simulation, and performance analysis of the proposed CMOS hybrid LNA. The work included transistor sizing, biasing, input matching, tuned load design, transformer-coupled stage analysis, simulation setup, and evaluation of gain, noise figure, and input matching.

## 👥 Team

This was an academic team project with four members.

## 📄 Project Report

The complete project report is uploaded above in the file.

## 📈 Results

Simulation plots and key results are uploaded in the above file.

## 🚀 Future Work

Possible future improvements include:

- Post-layout electromagnetic co-simulation.
- Improvement of transformer quality factor.
- Optimization of linearity parameters such as IIP3 and P1dB.
- Fabrication and experimental validation.
- Integration with a mixer and VCO to develop a complete X-band receiver front-end.

## 📚 Academic Context

Academic project completed as part of the Bachelor of Engineering in Electronics and Communication Engineering.

**Technology:** 45 nm CMOS  
**Operating Frequency:** 9.5 GHz  
**Application:** X-band Radar Receiver
