# Awesome-Quantum-Computing-Service

## Top Quantum Computing Service Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Quantum Cloud Access, Hybrid Algorithms & Open-Source Quantum Frameworks*  

**Last updated: October 2026**



This repository tracks notable **commercial quantum computing services** and **open-source projects** that provide access to quantum processors, simulators, and development frameworks. These platforms enable researchers and developers to run quantum circuits, optimize hybrid algorithms, and explore quantum advantage.



**Examples** include Azure Quantum, Amazon Braket, IBM Quantum Platform, Google Quantum AI, Rigetti Quantum Cloud Services, Xanadu Quantum Cloud, IonQ Quantum Cloud, D-Wave Leap, Quantinuum, and Strangeworks (the category leaders).



**Open-source emphasis**: Quantum computing is a domain where open-source software leads. **Qiskit** (IBM), **Cirq** (Google), **PennyLane** (Xanadu), and **ProjectQ** provide the foundational frameworks that power most quantum development, while **Catalyst** brings JIT compilation and **CUDA-Q** extends quantum programming to GPU-accelerated systems. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Azure Quantum](https://azure.microsoft.com/en-us/products/quantum)**  

  Microsoft's cloud quantum service providing access to multiple hardware providers (IonQ, Quantinuum, Rigetti, Pasqal) through a unified workspace. **Q# programming language with hardware-agnostic execution** — the same Q# code runs on any backend . Features **Resource Estimator** for measuring scalability, **Copilot** guidance for quantum coding, and **Azure Quantum Development Kit 1.0** with Rust-based core for speed and browser accessibility . Free to use without Azure account for code samples and Quantinuum Emulator .



- **[Amazon Braket](https://aws.amazon.com/braket/)**  

  AWS's fully managed quantum computing service with access to **IonQ, Rigetti, IQM, QuEra, and D-Wave** hardware. **Unified Python SDK** for building, testing, and running quantum circuits . Features **11 pre-built algorithm library** (Grover's, Shor's, QAOA, QBM, QFT, etc.), **Program Sets** for bundling up to 100 circuits into one task, and **Braket Direct** for exclusive hardware reservations with IonQ gate limit increased to 5,000 and error mitigation minimum reduced to 500 shots . **Tracker context manager** provides near-real-time cost estimates before submission .



- **[IBM Quantum Platform](https://quantum.ibm.com/)**  

  **The longest-running quantum cloud service** (since 2016) with **Heron QPU access for Open Plan users** . New enterprise-grade platform features **data locality** (choose EU datacenter), **enhanced security with SSO and Service IDs**, and **seamless integration with Cloud Object Storage and VPC** . **Qiskit** is the primary SDK. Classic platform sunset July 1, 2025 — migration to new platform required .



- **[Google Quantum AI](https://quantumai.google/)**  

  Google's quantum research division with **Willow chip** (105 qubits, 99.97% single-qubit fidelity, 99.88% entangling gates, 99.5% readout) . Achieved **first verifiable quantum advantage** with Quantum Echoes algorithm running 13,000x faster than classical supercomputers . **Cirq** is the primary open-source framework for programming Google's hardware.



- **[Rigetti Quantum Cloud Services](https://www.rigetti.com/)**  

  Cloud access to Rigetti's superconducting quantum processors. **Pioneered quantum co-processing** — hybrid classical-quantum architecture where quantum computers act as co-processors . **Quil** programming language and **Forest** SDK for development. Partners with NASA and DARPA for dynamic message scheduling .



- **[Xanadu Quantum Cloud](https://www.xanadu.ai/)**  

  Access to Xanadu's **photonic quantum computers** via cloud. **Aurora** is the first networked, modular, scalable quantum computer with **real-time error-correction decoding** . **Borealis** is the first public cloud-deployed computer with quantum computational advantage . **PennyLane** — the leading open-source quantum ML framework — powers Xanadu's software ecosystem with ~200K monthly downloads and ~35K active users .



- **[IonQ Quantum Cloud](https://ionq.com/)**  

  Access to IonQ's **trapped-ion quantum computers** with industry-leading gate fidelities. **Quantum Cloud Console** at cloud.ionq.com for managing API credentials and inspecting jobs . **Supports the most SDKs, languages, and cloud integrations** of any quantum hardware provider — use your preferred tools with IonQ hardware . **Aria** and **Forte** systems available.



- **[D-Wave Leap](https://www.dwavequantum.com/solutions-and-products/cloud-platform/)**  

  **The most commercially mature quantum cloud service** with 99.9% uptime and subsecond QPU response times . Access to **Advantage2 annealing quantum systems** and **hybrid solvers handling up to 2 million variables** . **SOC 2 Type 2 compliant** with enterprise-grade security . **The best platform for optimization problems** — scheduling, routing, resource allocation .



- **[Quantinuum](https://www.quantinuum.com/)**  

  **The world's most accurate commercial quantum computers** based on trapped-ion QCCD architecture with industry-leading two-qubit gate fidelity . **Helios** launched commercially in 2025, enabling **Generative Quantum AI (GenQAI)** . Received **$100M CHIPS R&D award** for trapped-ion manufacturing with GlobalFoundries and Monarch Quantum . **H-Series** and **System Model H1/H2** available via Azure Quantum and direct access.



- **[Strangeworks](https://strangeworks.com/)**  

  **Unified platform for quantum, quantum-inspired, HPC, and classical compute** — one interface, any backend . Access to optimization solvers, quantum hardware, and frameworks with **one-click activation and zero markup on compute** . Features **unified billing, team management, enterprise security, and priority support** . **The best platform for comparing across providers** — switch backends with one line of code .



## Open-Source GitHub Projects



- **[Qiskit](https://github.com/Qiskit/qiskit)**  

  **The most widely adopted open-source quantum SDK**, Apache-2.0 licensed . **IBM's quantum computing framework** for building, simulating, and running quantum circuits on IBM hardware and simulators . Features **Terra (circuit construction), Aer (high-performance simulators), and Ignis (noise characterization)** . **The de facto standard for quantum programming** — used by researchers, educators, and enterprises worldwide. **Best for general-purpose quantum development and IBM hardware access** .



- **[Cirq](https://github.com/quantumlib/Cirq)**  

  **Google's open-source quantum computing framework**, Apache-2.0 licensed . **Designed for NISQ-era algorithms** — precise control over quantum circuits and gates . **Native support for Google's Sycamore and Willow processors** . Features **circuit optimization, noise modeling, and quantum virtual machine (qsim)** . **Best for Google hardware and NISQ algorithm development** .



- **[PennyLane](https://github.com/PennyLaneAI/pennylane)**  

  **The leading open-source quantum machine learning framework**, Apache-2.0 licensed with **2,000+ GitHub stars** . **Differentiable quantum programming** — integrates with PyTorch, TensorFlow, and JAX . **Hardware-agnostic** — runs on IBM, Google, Rigetti, IonQ, Xanadu, and simulators . **~200K monthly downloads and ~35K active users** . **The best framework for quantum ML and hybrid quantum-classical optimization** . **Catalyst** provides JIT compilation for hybrid programs .



- **[ProjectQ](https://github.com/ProjectQ-Framework/ProjectQ)**  

  **Open-source quantum computing framework from ETH Zurich**, Apache-2.0 licensed . **Compiler-focused architecture** — separates high-level algorithm description from hardware execution . Features **circuit optimization, resource estimation, and multiple backends** (IBM, Rigetti, AQT, IonQ) . **Fermilib** for quantum chemistry and **mathlib** for high-level quantum operations . **Best for compiler research and resource estimation** .



- **[Q# (Microsoft Quantum Development Kit)](https://github.com/microsoft/qsharp)**  

  **Microsoft's open-source quantum programming language and QDK**, MIT licensed . **Hardware-agnostic language** — no notion of quantum state or circuit, describes how classical control interacts with qubits . **Rust-based core for speed and portability** . **Azure Quantum Resource Estimator** for scalability measurement . **Best for Microsoft ecosystem and hybrid quantum-classical programming** .



- **[Strawberry Fields](https://github.com/XanaduAI/strawberryfields)**  

  **Xanadu's open-source photonic quantum computing library**, Apache-2.0 licensed . **Continuous-variable (CV) quantum computing** — the foundation for Xanadu's photonic hardware . **Blackbird** is the quantum programming language for CV systems . **The reference for photonic quantum programming** — though Xanadu Quantum Cloud has been archived and replaced by PennyLane . **Best for photonic quantum computing research** .



- **[Catalyst](https://github.com/PennyLaneAI/catalyst)**  

  **JIT compiler for hybrid quantum programs in PennyLane**, Apache-2.0 licensed with **93 GitHub stars** . **MLIR-based compilation stack** — the industry's most downloaded quantum MLIR compiler . Enables **just-in-time compilation of quantum-classical hybrid programs** for improved performance . **Best for optimizing hybrid quantum-classical workflows** .



- **[CUDA-Q Logical](https://github.com/NVIDIA/cuda-quantum)**  

  **NVIDIA's open-source quantum programming platform**, Apache-2.0 licensed . **CUDA-Q Logical** expands to **fault-tolerant quantum computing** with open, extensible logical layer for quantum error correction . **GPU-accelerated quantum simulation** — the fastest way to simulate quantum circuits . **Best for GPU-accelerated quantum development and error correction research** .



- **[Tweedledum](https://github.com/boschmitt/tweedledum)**  

  **C++17 library for quantum circuit analysis, compilation, and optimization**, MIT licensed with **92 GitHub stars** . **The reference for quantum circuit optimization** — used by many other compilers. **Best for quantum compiler development** .



- **[QuTiP](https://github.com/qutip/qutip)**  

  **Quantum Toolbox in Python** — open-source framework for simulating quantum systems, Apache-2.0 licensed . **The standard for quantum physics simulation** — open quantum systems, master equations, and quantum optics . **Best for physics research and quantum dynamics simulation** .



- **[OpenFermion](https://github.com/quantumlib/OpenFermion)**  

  **Google's open-source library for quantum chemistry**, Apache-2.0 licensed . **The standard for electronic structure calculations** — molecular Hamiltonians, fermionic operators, and qubit mappings . **Best for quantum chemistry and materials science** .



- **[Yao.jl](https://github.com/QuantumBFS/Yao.jl)**  

  **Julia-based quantum algorithm framework**, Apache-2.0 licensed . **Extensible design** — build custom quantum algorithms . **QuAlgorithmZoo.jl** provides curated algorithm implementations . **Best for Julia users and algorithm research** .



### Additional Strong Open-Source Options



- **Cirq-Google** — Native Cirq support for Google hardware .

- **Qiskit-Braket-Provider** — Qiskit integration for Amazon Braket .

- **PennyLane-Cirq** — PennyLane plugin for Cirq integration .

- **PyQtorch** — PyTorch-based quantum simulator .

- **sQUlearn** — scikit-learn interface for quantum algorithms .

- **TensorFlow Quantum** — Google's quantum ML library (archived) .

- **QuTiP** — Quantum Toolbox in Python .

- **ProjectQ** — Compiler-focused quantum framework .

- **Tweedledum** — Quantum circuit optimization .

- **UniversalQCompiler** — Synthesizing arbitrary quantum computations .



**Frameworks for building custom quantum solutions**: Choose based on hardware target and use case. **Qiskit** for IBM hardware and general-purpose development . **Cirq** for Google hardware and NISQ algorithms . **PennyLane** for quantum ML and hybrid optimization with hardware-agnostic execution . **ProjectQ** for compiler research and resource estimation . **Q#** for Microsoft ecosystem and hardware-agnostic programming . **CUDA-Q Logical** for GPU-accelerated simulation and error correction . Note that true quantum advantage with fault-tolerant systems remains years away; current NISQ-era platforms provide value in hybrid optimization (D-Wave Leap), quantum chemistry (OpenFermion), and algorithm research.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Quantum computing services provide access to experimental hardware with limited qubit counts and error rates. **Results are not guaranteed** — quantum advantage demonstrations are specific to particular problems and implementations.

- **Costs vary significantly** — Amazon Braket provides near-real-time cost estimates via Tracker context manager . D-Wave Leap is SOC 2 Type 2 compliant with enterprise pricing . Review pricing before committing to large workloads.

- **Open-source frameworks are vendor-neutral but hardware-specific** — Qiskit targets IBM, Cirq targets Google, PennyLane is hardware-agnostic . Choose based on your hardware access.

- **The quantum ecosystem is rapidly evolving** — IBM Quantum Platform Classic sunset July 1, 2025 . Xanadu Quantum Cloud has been archived . Verify current platform status before committing.

- The open-source ecosystem provides strong quantum SDKs, simulators, and algorithms, but **fault-tolerant quantum computing with verifiable advantage** remains primarily a research milestone achieved on specific hardware (Google Willow) .



---



**Made for quantum researchers, algorithm developers, and enterprises exploring quantum computing.**

Let's make quantum computing more open, transparent, and accessible.
