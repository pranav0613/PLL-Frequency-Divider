# 🔄 Phase-Locked Loop (PLL) Frequency Divider
Mixed-Signal Circuit Simulation & Analysis

## 📖 Project Overview
This repository contains the simulation netlist and waveform analysis for a Frequency Divider built using a Phase-Locked Loop (PLL) architecture. The project demonstrates the integration of analog and digital components to actively lock onto a reference frequency and scale it down via a feedback loop.

## 🛠️ Technical Stack
Simulation Tool: Falstad Circuit Simulator

Design Domain: Analog / Mixed-Signal Electronics

Core Mechanisms: Phase detection, low-pass filtering, and voltage-controlled oscillation (VCO).

## 🧠 Circuit Architecture
The circuit leverages the classic PLL feedback loop to achieve frequency division. By placing a digital divider (counter) in the feedback path between the VCO and the Phase Detector, the VCO is forced to oscillate at a multiple of the input reference frequency.

System Components:
Phase Detector: Compares the phase of the reference input with the feedback signal.

Low-Pass Filter (LPF): Extracts the DC error voltage and dampens high-frequency noise.

Voltage Controlled Oscillator (VCO): Generates the high-frequency output based on the error voltage.

Frequency Divider: Scales down the VCO output before feeding it back to the Phase Detector.

## 📈 Simulation & Waveform Analysis
The simulation validates the locking mechanism and the resulting divided frequency.

Circuit Schematic & Transient Response
The Falstad simulation showing the closed-loop architecture and the transient waveform response of the divided output.

## 🚀 Key Learning Outcomes
Analyzed closed-loop control systems within mixed-signal electronics.

Validated the mathematical relationship between the reference frequency, the divider modulus, and the VCO output.

Mastered transient simulation and waveform debugging using Falstad.
