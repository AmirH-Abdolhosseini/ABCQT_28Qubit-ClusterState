# Quantum Teleportation Protocol using a 28-Qubit Cluster State Channel

This repository implements the **Circular Asymmetric Bidirectional Quantum Teleportation (CABQT)** protocol, utilizing a **28-qubit cluster state** as the quantum channel. The project simulates the quantum teleportation process for 2-qubit and 3-qubit states, analyzes the impact of **depolarizing noise**, and evaluates the protocol's robustness using **Qiskit**.

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction
Quantum teleportation is a fundamental concept in quantum information science, enabling the transfer of quantum states between distant parties without physical transport of the particles. This project simulates the **CABQT** protocol, where **four participants** (Alice, Bob, Charlie, and Frank) share a **28-qubit cluster state** as a quantum channel for teleportation.

The primary aim of this project is to simulate the behavior of the CABQT protocol using **Qiskit** and evaluate its performance in the presence of **depolarizing noise**—one of the most challenging forms of noise in quantum teleportation. The project provides insights into how noise can affect the teleportation process, using simulations of both **2-qubit** and **3-qubit states**.

## Project Overview
The repository contains:
- A Jupyter notebook (**`ABCQT_Teleportation_Protocol_28_Qubit_ClusterStateChannel.ipynb`**) that simulates the quantum teleportation protocol, including noise and fidelity analysis.
- Simulations of **2-qubit** and **3-qubit states** demonstrating the role of Alice (the sender) in the protocol.
- Noise simulations that apply **depolarizing noise** to observe its impact on the teleportation fidelity.
- Fidelity analysis comparing the initial and teleported states to understand how the presence of noise affects the protocol's accuracy.

### Notebook Features:
- **Quantum Circuit Simulation**: Implements the CABQT protocol for teleportation.
- **Depolarizing Noise Simulation**: Analyzes the effects of depolarizing noise on quantum states.
- **Fidelity Analysis**: Measures and visualizes the fidelity of teleportation under different noise levels.
- **Visualizations**: Plots and histograms to compare the initial and final states, showing the noise effects on the teleportation process.

## Key Features
- **Quantum Teleportation Simulation**: Models both 2-qubit and 3-qubit teleportation using the CABQT protocol.
- **Noise Impact Analysis**: Simulates depolarizing noise and analyzes its destructive effect on the teleportation process.
- **Fidelity Measurement**: Tracks the fidelity between the original and teleported states to assess the accuracy of the protocol under noise.
- **Interactive Visuals**: Includes detailed visualizations, such as histograms and bar charts, to demonstrate the impact of noise and the state measurements.

## Installation
To set up and run this project, you’ll need Python and the necessary packages. You can install them with the following commands:

```bash
pip install qiskit[visualization]
pip install pylatexenc
pip install qiskit-aer
