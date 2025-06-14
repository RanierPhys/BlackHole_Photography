# Black Hole Photography Simulator

![Python](https://img.shields.io/badge/Python-3.8+-blue)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

<p align="center">
  <img src="images/simulation_example.png" width="70%">
  <br><em>Simulated view of a Schwarzschild black hole with thin accretion disk</em>
</p>

## Table of Contents
- [Physics Background](#-physics-background)
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Repository Structure](#-repository-structure)
- [Example Results](#-example-results)
- [Team](#-team)
- [License](#-license)

## 🌌 Physics Background
This simulator computes photon trajectories in Schwarzschild spacetime, demonstrating:
- **Light bending** near the event horizon
- **Photon sphere** at r = 3GM/c²
- **Relativistic effects**:
  - Doppler beaming
  - Gravitational redshift
- **Thin accretion disk** physics (Novikov-Thorne model)

The geodesic equations are solved numerically:
```math
\frac{d^2x^\mu}{d\lambda^2} + \Gamma^\mu_{\alpha\beta}\frac{dx^\alpha}{d\lambda}\frac{dx^\beta}{d\lambda} = 0
```


🚀 Features
Interactive PyQT5 interface

Real-time parameter control:

Black hole mass

Viewing angle (0°-90°)

Disk temperature profile

Multiple visualization modes

Export simulation data

🛠️ Installation
Clone repository:

git clone https://github.com/RanierPhys/BlackHole_Photography.git



python src/main.py

BlackHole_Photography/
├── src/
│   ├── physics/          # Core calculations
│   │   ├── geodesics.py
│   │   └── disk_model.py
│   ├── ui/               # Interface code
│   │   ├── main_window.py
│   │   └── widgets.py
│   └── visualization/    # Plotting tools
├── data/                 # Simulation outputs
├── images/               # Example images
├── requirements.txt      # Dependencies
└── LICENSE

Team
Ranier Menote - Physics modeling

[Teammate 1] - UI development

[Teammate 2] - Visualization
