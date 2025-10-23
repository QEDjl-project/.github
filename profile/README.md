# QuantumElectrodynamics.jl: A strong-field particle physics ecosystem

[![Documentation](https://img.shields.io/badge/documentation-blue?style=for-the-badge&logoColor=white)](https://qedjl-project.github.io/QuantumElectrodynamics.jl/stable/) [![Julia](https://img.shields.io/badge/-Julia-9558B2?style=for-the-badge&logo=julia&logoColor=white)](https://julialang.org) 

Welcome to **QEDjl-project**, a family of Julia packages for computations and simulations in relativistic quantum electrodynamics (QED) with a particular focus on strong-field phenomena and scattering processes. The key package, `QuantumElectrodynamics.jl`, provides the central framework, and it is supported by a set of interoperable sub-packages, each addressing core components.

### Why this project  
- To provide a **modern, high-performance Julia toolkit** for QED and strong-field particle physics.  
- To integrate interfaces for **Lorentz vectors, spinors, particles, phase-space and scattering processes**, enabling end-to-end simulation workflows.  
- To maintain an **open-source, modular architecture**, so that researchers, and developers can extend, integrate or embed these capabilities in larger simulation systems.

## Key Packages  
Below is a selection of the core physics packages within the QEDjl-project ecosystem:

<div align="center">

| Package | Purpose | Status | Version |
|---------|---------|---------|---------|
| [`QuantumElectrodynamics.jl`](https://github.com/QEDjl-project/QuantumElectrodynamics.jl/) | umbrella package which brings everything together | [![][badge-qedjl-pipeline]][main-qedjl-pipeline] | [![][badge-qedjl-version]][status-qedjl-version]|
| [`QEDbase.jl`](https://github.com/QEDjl-project/QEDbase.jl/) | Fundamental interfaces | [![][badge-base-pipeline]][main-base-pipeline] | [![][badge-base-version]][status-base-version]|
| [`QEDcore.jl`](https://github.com/QEDjl-project/QEDcore.jl/) | Fundamental data types and core functions| [![][badge-core-pipeline]][main-core-pipeline] | [![][badge-core-version]][status-core-version]|
| [`QEDprocesses.jl`](https://github.com/QEDjl-project/QEDprocesses.jl/) | Modeling scattering processes: probabilities, cross sections, process definitions. | [![][badge-procs-pipeline]][main-procs-pipeline] | [![][badge-procs-version]][status-procs-version]|
| [`QEDevents.jl`](https://github.com/QEDjl-project/QEDevents.jl/) | Monte-Carlo event generation |[![][badge-events-pipeline]][main-events-pipeline] | [![][badge-events-version]][status-events-version]|
| [`QEDfields.jl`](https://github.com/QEDjl-project/QEDfields.jl/) | Modeling of electromagnetic fields, e.g., for strong-field backgrounds.|[![][badge-fields-pipeline]][main-fields-pipeline] | [![][badge-fields-version]][status-fields-version]|
| [`QEDFeynmanDiagrams.jl`](https://github.com/QEDjl-project/QEDFeynmanDiagrams.jl/) | Automatic generation of Feynman diagrams for perturbative QED |[![][badge-feyndiags-pipeline]][main-feyndiags-pipeline] | [![][badge-feyndiags-version]][status-feyndiags-version]|

</div>

## Support Packages
Additionally, the following are also monitored and developed for the QEDjl project:

<div align="center">

| Package | Purpose | Status | Version |
|---------|---------|---------|---------|
| [`ComputableDAGs.jl`](https://github.com/ComputableDAGs/ComputableDAGs.jl) | Representation of Computations as Directed Acyclic Graphs | [![][badge-cdags-pipeline]][main-cdags-pipeline] | [![][badge-cdags-version]][status-cdags-version]|
| [`IntegrationTests.jl`](https://github.com/QEDjl-project/IntegrationTests.jl) | Representation of Computations as Directed Acyclic Graphs | [![][badge-integtests-pipeline]][main-integtests-pipeline] | [![][badge-integtests-version]][status-integtests-version]|

</div>

<!-- pipeline status -->

[badge-qedjl-pipeline]: https://img.shields.io/gitlab/pipeline-status/hzdr%2Fqedjl-project%2FQED-jl?branch=main&logo=GitLab&label=CI
[main-qedjl-pipeline]: https://gitlab.com/hzdr/qedjl-project/QED-jl/-/commits/main

[badge-base-pipeline]: https://img.shields.io/gitlab/pipeline-status/hzdr%2Fqedjl-project%2FQEDbase-jl?branch=main&logo=GitLab&label=CI
[main-base-pipeline]: https://gitlab.com/hzdr/qedjl-project/QEDbase-jl/-/commits/main

[badge-core-pipeline]: https://img.shields.io/gitlab/pipeline-status/hzdr%2Fqedjl-project%2Fqedcore.jl?branch=main&logo=GitLab&label=CI
[main-core-pipeline]: https://gitlab.com/hzdr/qedjl-project/qedcore.jl/-/commits/main

[badge-procs-pipeline]: https://img.shields.io/gitlab/pipeline-status/hzdr%2Fqedjl-project%2FQEDprocesses-jl?branch=main&logo=GitLab&label=CI
[main-procs-pipeline]: https://gitlab.com/hzdr/qedjl-project/QEDprocesses-jl/-/commits/main

[badge-events-pipeline]: https://img.shields.io/gitlab/pipeline-status/hzdr%2Fqedjl-project%2FQEDevents-jl?branch=main&logo=GitLab&label=CI
[main-events-pipeline]: https://gitlab.com/hzdr/qedjl-project/QEDevents-jl/-/commits/main

[badge-fields-pipeline]: https://img.shields.io/gitlab/pipeline-status/hzdr%2Fqedjl-project%2FQEDfields-jl?branch=main&logo=GitLab&label=CI
[main-fields-pipeline]: https://gitlab.com/hzdr/qedjl-project/QEDfields-jl/-/commits/main

[badge-feyndiags-pipeline]: https://img.shields.io/gitlab/pipeline-status/hzdr%2Fqedjl-project%2FQEDFeynmanDiagrams-jl?branch=main&logo=GitLab&label=CI
[main-feyndiags-pipeline]: https://gitlab.com/hzdr/qedjl-project/QEDFeynmanDiagrams-jl/-/commits/main

[badge-cdags-pipeline]: https://img.shields.io/github/actions/workflow/status/ComputableDAGs/ComputableDAGs.jl/unit_tests.yml?label=CI&logo=GitHub
[main-cdags-pipeline]: https://github.com/ComputableDAGs/ComputableDAGs.jl/actions/workflows/unit_tests.yml

[badge-integtests-pipeline]: https://img.shields.io/github/actions/workflow/status/QEDjl-project/IntegrationTests.jl/CI.yml?label=CI&logo=GitHub
[main-integtests-pipeline]: https://github.com/QEDjl-project/IntegrationTests.jl/actions/workflows/CI.yml

<!-- versions -->

[badge-qedjl-version]: https://juliahub.com/docs/General/QuantumElectrodynamics/stable/version.svg
[status-qedjl-version]: https://juliahub.com/ui/Packages/General/QuantumElectrodynamics

[badge-base-version]: https://juliahub.com/docs/General/QEDbase/stable/version.svg
[status-base-version]: https://juliahub.com/ui/Packages/General/QEDbase

[badge-core-version]: https://juliahub.com/docs/General/QEDcore/stable/version.svg
[status-core-version]: https://juliahub.com/ui/Packages/General/QEDcore

[badge-procs-version]: https://juliahub.com/docs/General/QEDprocesses/stable/version.svg
[status-procs-version]: https://juliahub.com/ui/Packages/General/QEDprocesses

[badge-fields-version]: https://juliahub.com/docs/General/QEDfields/stable/version.svg
[status-fields-version]: https://juliahub.com/ui/Packages/General/QEDfields

[badge-events-version]: https://juliahub.com/docs/General/QEDevents/stable/version.svg
[status-events-version]: https://juliahub.com/ui/Packages/General/QEDevents

[badge-feyndiags-version]: https://juliahub.com/docs/General/QEDFeynmanDiagrams/stable/version.svg
[status-feyndiags-version]: https://juliahub.com/ui/Packages/General/QEDFeynmanDiagrams

[badge-cdags-version]: https://juliahub.com/docs/General/ComputableDAGs/stable/version.svg
[status-cdags-version]: https://juliahub.com/ui/Packages/General/ComputableDAGs

[badge-integtests-version]: https://juliahub.com/docs/General/IntegrationTests/stable/version.svg
[status-integtests-version]: https://juliahub.com/ui/Packages/General/IntegrationTests
