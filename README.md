# Supercomputing for Modeling and Simulation — Summer School 2026

**Centre for AI & Big Data (CAID), Namal University, Mianwali**  
**22–23 August 2026 · Executive Hall · Namal University, Mianwali, Pakistan**

This repository archives the lecture material for the **Two-Day Summer School on Supercomputing for Modeling and Simulation**. The program introduced the complete path from scientific models to practical high-performance-computing (HPC) execution, including modeling paradigms, HPC architecture, scientific software, Slurm-based execution, molecular dynamics, quantum simulation, performance profiling, optimization, and scaling.

> **Core idea:** Real problem → Mathematical model → Simulation → HPC execution → Results → Decision/impact

## Course objectives

The summer school was designed to help participants:

- understand the role of HPC in scientific modeling and simulation;
- move from mathematical/physical models to numerical simulations;
- understand CPU, GPU, memory, storage, and interconnect requirements for scientific workloads;
- work in a Linux-based HPC environment;
- use software modules and the Slurm workload manager;
- understand MPI, OpenMP, GPU acceleration, and hybrid parallelism;
- prepare and run introductory GROMACS and Quantum ESPRESSO workflows;
- understand the role of OpenFOAM and other scientific-software ecosystems;
- monitor resource utilization and identify compute-, memory-, communication-, and I/O-bound behavior;
- apply basic performance profiling, optimization, benchmarking, and scaling practices.

## Lecture material

| # | Lecture | Presenter | File |
|---|---|---|---|
| 1 | Modeling & Simulation for National Development — Building Pakistan’s Indigenous HPC and Computational Capability | Prof. Dr. Tassadaq Hussain | [`01_modeling_simulation_for_national_development.pdf`](lectures/01_modeling_simulation_for_national_development.pdf) |
| 2 | Fundamentals of Modeling & Simulation | Amna Haider — Co-Founder, Pakistan Supercomputing; CEO, UCERD Pvt Ltd | [`02_fundamentals_of_modeling_and_simulation.pdf`](lectures/02_fundamentals_of_modeling_and_simulation.pdf) |
| 3 | High-Performance Computing for Scientific Modeling and Simulation | Prof. Dr. Tassadaq Hussain | [`03_hpc_for_scientific_modeling_and_simulation.pdf`](lectures/03_hpc_for_scientific_modeling_and_simulation.pdf) |
| 4 | Scientific Software Stack and Running Simulations on HPC | Prof. Dr. Tassadaq Hussain | [`04_scientific_software_stack_and_running_simulations_on_hpc.pdf`](lectures/04_scientific_software_stack_and_running_simulations_on_hpc.pdf) |
| 5 | Scientific Software Ecosystem for HPC — From Physical Models to Large-Scale Simulations | Mushafia Sadia Aman — Researcher, HPC Systems for Modeling and Simulations, CAID | [`05_scientific_software_ecosystem_for_hpc.pdf`](lectures/05_scientific_software_ecosystem_for_hpc.pdf) |
| 6 | Molecular Dynamics Simulations with GROMACS — Protein–Protein & Protein–Drug Interactions and CHARMM-GUI | Dr. Najumuddin — Hamdard University, Karachi | [`06_molecular_dynamics_simulations_with_gromacs.pdf`](lectures/06_molecular_dynamics_simulations_with_gromacs.pdf) |
| 7 | HPC Performance Optimization, Scaling & Collaborative Scientific Computing | Prof. Dr. Tassadaq Hussain | [`07_hpc_performance_optimization_scaling_and_collaboration.pdf`](lectures/07_hpc_performance_optimization_scaling_and_collaboration.pdf) |

A compact lecture index is also available in [`lectures/README.md`](lectures/README.md).

## Major topics

### Modeling and simulation
- physical vs computational experiments;
- mathematical models, assumptions, initial and boundary conditions;
- verification, validation, and uncertainty;
- mesh/continuum, particle/atomistic, agent/discrete-event, and hybrid/multiscale paradigms;
- scientific workflow from problem definition to decision-quality results.

### HPC architecture
- laptop → workstation → server → HPC cluster → supercomputer;
- compute nodes, CPUs, GPUs, memory hierarchy, storage, and network;
- shared-memory and distributed-memory systems;
- heterogeneous CPU/GPU computing;
- suitability of professional scientific-computing hardware for large workloads.

### Parallel computing
- serial vs parallel execution;
- domain decomposition;
- task/functional parallelism;
- ensemble/parameter-sweep parallelism;
- data parallelism;
- MPI, OpenMP, CUDA/GPU execution, and hybrid parallelism;
- synchronous vs asynchronous execution.

### HPC software and scheduling
- Linux and environment modules;
- compilers, mathematical libraries, MPI/OpenMP/CUDA runtimes;
- Slurm resource requests, batch scripts, queues, monitoring, and accounting;
- shared storage and reproducible project organization.

### Scientific applications
- **GROMACS:** molecular dynamics, force fields, topology, solvation, ions, energy minimization, NVT/NPT equilibration, production runs, and trajectory analysis;
- **Quantum ESPRESSO:** DFT, SCF calculations, k-point, band/state, FFT, and linear-algebra parallelism;
- **OpenFOAM:** mesh-based CFD, domain decomposition, parallel execution, and post-processing.

### Performance engineering
- profiling before optimization;
- execution time and throughput;
- CPU/GPU utilization;
- memory bandwidth and locality;
- MPI/network communication;
- I/O behavior;
- strong and weak scaling;
- speedup and parallel efficiency;
- choosing MPI ranks, threads, GPUs, and decomposition strategies.

## Practical learning

The summer school included guided work on:

- Linux access and software modules;
- Slurm job creation, submission, monitoring, and cancellation;
- GROMACS molecular-dynamics workflow;
- Quantum ESPRESSO input preparation and execution;
- MPI scaling and resource-utilization analysis;
- simulation output processing and visualization.

## Technical environment

The instructional environment covered:

- Namal Supercomputing Facility;
- Linux command-line environment;
- Slurm workload manager;
- Environment Modules;
- MPI and OpenMP;
- GROMACS;
- Quantum ESPRESSO;
- OpenFOAM;
- scientific visualization and post-processing tools.

## Intended audience

The material is suitable for:

- undergraduate and graduate students;
- researchers and academic faculty;
- engineers and professionals in physics, chemistry, materials science, biotechnology, and mechanical engineering;
- computational scientists and practitioners entering HPC-enabled modeling and simulation.

### Recommended prerequisites

- basic Linux command-line familiarity;
- basic scientific-computing or numerical-simulation knowledge.

Prior experience with HPC, GROMACS, Quantum ESPRESSO, OpenFOAM, MPI, or Slurm is useful but not required for reading the lecture material.

## Repository organization

```text
.
├── README.md
├── CITATION.cff
├── LICENSE-MATERIALS.md
├── THIRD_PARTY_NOTICE.md
├── CONTRIBUTING.md
├── GITHUB_SETUP.md
├── SHA256SUMS.txt
└── lectures/
    ├── README.md
    ├── 01_modeling_simulation_for_national_development.pdf
    ├── 02_fundamentals_of_modeling_and_simulation.pdf
    ├── 03_hpc_for_scientific_modeling_and_simulation.pdf
    ├── 04_scientific_software_stack_and_running_simulations_on_hpc.pdf
    ├── 05_scientific_software_ecosystem_for_hpc.pdf
    ├── 06_molecular_dynamics_simulations_with_gromacs.pdf
    └── 07_hpc_performance_optimization_scaling_and_collaboration.pdf
```

## Citation

If these materials support teaching, research, or training, please cite the repository. GitHub can generate citation information automatically from [`CITATION.cff`](CITATION.cff).

Suggested human-readable citation:

> Hussain, T., Haider, A., Aman, M. S., & Najumuddin. (2026). *Supercomputing for Modeling and Simulation: Summer School Lecture Material*. Centre for AI & Big Data (CAID), Namal University, Mianwali. Two-Day Summer School, 22–23 August 2026.

If citing a specific lecture, cite the individual presenter and lecture title shown in the lecture table.

## Organizers and contributors

**Centre for AI & Big Data (CAID)**  
Namal University, Mianwali, Pakistan

**Lead Trainer**  
Prof. Dr. Tassadaq Hussain  
Director, Centre for AI & Big Data (CAID)

**Contributing trainers / presenters**
- Amna Haider — Pakistan Supercomputing / UCERD Pvt Ltd
- Mushafia Sadia Aman — CAID, Namal University
- Dr. Najumuddin — Hamdard University, Karachi

## Useful links

- CAID: https://caid.namal.edu.pk
- UCERD GitHub organization: https://github.com/ucerd

## Copyright, licensing, and third-party material

These lecture PDFs contain material created by multiple presenters and may also contain logos, screenshots, figures, photographs, software names, or other third-party material.

**Do not apply a blanket open-source or Creative Commons license to all PDFs unless the rights for every lecture and third-party component have been confirmed.** See [`LICENSE-MATERIALS.md`](LICENSE-MATERIALS.md) and [`THIRD_PARTY_NOTICE.md`](THIRD_PARTY_NOTICE.md).

If software, scripts, or original example code are added later, they should be placed under a separate code license (for example MIT, BSD-3-Clause, or Apache-2.0) only after the repository owners choose the appropriate terms.

## Reproducibility note

Scientific-computing results depend on software version, compiler, MPI implementation, numerical libraries, hardware, resource allocation, and input parameters. When adding practical examples, preserve:

- exact application version;
- module/environment information;
- Slurm script;
- input files;
- output/log files;
- node/CPU/GPU allocation;
- relevant performance metrics.

This allows others to distinguish **scientific correctness** from **performance behavior** and to reproduce the execution environment more reliably.

## Contact

Centre for AI & Big Data (CAID)  
Namal University, 30 km Talagang Road, Mianwali, Pakistan  
Email: office_ai_centre@namal.edu.pk  
Phone: +92 315 6476325 | Ext. 164

---

**Event:** Two-Day Summer School on Supercomputing for Modeling and Simulation  
**Dates:** 22–23 August 2026  
**Venue:** Executive Hall, Namal University, Mianwali
