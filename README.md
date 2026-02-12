# Electronic Circuit Design & Characterization Portfolio

[cite_start]A collection of high-performance analog and power electronics projects developed at **Tecnológico de Monterrey**[cite: 610, 612]. This repository documents the design, simulation, and physical implementation of fundamental electronic systems.

## 🚀 Projects Overview

### 1. Instrumentation Amplifier & Signal Conditioning
[cite_start]Designed a high-precision instrumentation amplifier using the **TL084 OpAmp**[cite: 787, 798]. 
* [cite_start]**Key Feature:** Achieved effective rejection of a 1V common-mode offset, outputting only the amplified differential signal[cite: 782, 783, 844].
* [cite_start]**Applications:** Sensor data acquisition and small-signal conditioning[cite: 783, 863].

### 2. Audio Power Amplifier (Push-Pull)
[cite_start]Developed a "Mono" audio amplifier combining an inverting OpAmp stage for gain control with a **TIP41C/TIP42C complementary push-pull stage**[cite: 978, 1012].
* [cite_start]**Performance:** Capable of driving an 8Ω speaker with high current (up to 6A) and minimal harmonic distortion[cite: 980, 1013, 1065].

### 3. Adjustable Voltage Regulator (1V - 12V)
[cite_start]Implemented a series linear regulator using an **LM358 OpAmp**, a Zener diode reference, and a **TIP31C power transistor**[cite: 869, 873].
* [cite_start]**Specs:** Adjustable output from 0.1V up to 12.3V with high-current stability (up to 300mA)[cite: 873, 943, 949, 957].

### 4. Signal Generation & PWM Motor Control
* [cite_start]**Waveform Generator:** Designed an oscillator for simultaneous square and triangular wave generation[cite: 1069, 1074].
* [cite_start]**DC Motor Control:** Implemented a speed control system using an **NE555 timer** for Pulse Width Modulation (PWM) to drive a DC motor via a chopper converter[cite: 1132, 1133, 1146].

## 📊 Characterization & Analysis
Each project includes detailed mathematical modeling and experimental verification:
* [cite_start]**Frequency Analysis:** Bode plots for Integrator/Differentiator circuits[cite: 752, 774].
* [cite_start]**Thermal Modeling:** Calculated heat sink requirements ($R_{\theta}$ ≈ 22.83°C/W) for power transistors[cite: 1017].
* [cite_start]**Efficiency:** Evaluation of power dissipation and conversion efficiency in linear vs. switching topologies[cite: 935, 936].

## 🛠️ Tools Used
* [cite_start]**Hardware:** Oscilloscopes (Keysight InfiniVision), Multimeters, Function Generators[cite: 623, 637, 641, 648].
* [cite_start]**Components:** TL084, LM358, NE555, TIP31C/41C/42C[cite: 787, 869, 1012, 1146].
