# QuantumElectrodynamics.jl: A strong-field particle physics ecosystem

[![Docs](https://img.shields.io/badge/docs-stable-blue)](https://qedjl-project.github.io/QuantumElectrodynamics.jl/stable/)  

Welcome to **QEDjl-project**, a family of Julia packages for computations and simulations in relativistic quantum electrodynamics (QED) with a particular focus on strong-field phenomena and scattering processes. The key package, `QuantumElectrodynamics.jl`, provides the central framework, and it is supported by a set of interoperable sub-packages, each addressing core components.

### Why this project  
- To provide a **modern, high-performance Julia toolkit** for QED and strong-field particle physics.  
- To integrate interfaces for **Lorentz vectors, spinors, particles, phase-space and scattering processes**, enabling end-to-end simulation workflows.  
- To maintain an **open-source, modular architecture**, so that researchers, and developers can extend, integrate or embed these capabilities in larger simulation systems.

## Key Packages  
Below is a selection of the core packages within the QEDjl-project ecosystem:

| Package | Purpose |
|---------|---------|
| `QuantumElectrodynamics.jl` | The umbrella package: brings together interfaces, utilities and glue logic across sub-packages. |
| `QEDbase.jl` | Fundamental data types and interfaces: Lorentz vectors, bi-spinors, Dirac matrices, particle states.|
| `QEDcore.jl` | Core functions, mutable types and advanced operations built on base interfaces.|
| `QEDprocesses.jl` | Modeling scattering processes: probabilities, cross sections, process definitions. |
| `QEDevents.jl` | Monte-Carlo event generation and simulation of scattering outcomes. |
| `QEDfields.jl` | Representation and modeling of electromagnetic fields (e.g., strong-field backgrounds).|
| `QEDFeynmanDiagrams.jl` | Automatic generation of Feynman diagrams for perturbative QED, with integration into computational DAGs.|

