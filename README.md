# QAMP2025BatteryDegradation

QAMP Project Proposal: Quantum-Enhanced Mapping of Battery Degradation Pathways
Description
The aim of this project is to design and implement a quantum-enhanced simulation framework for mapping the transition states of ethylene glycol oxidation, a critical degradation pathway in battery electrolytes. The focus is on computing reaction coordinate profiles using the Quantum Subspace Diagonalization (QSD) method, integrated with modern Qiskit chemistry and quantum algorithm libraries.

Accurately capturing transition states within 0.1 eV error tolerance is essential to understanding degradation mechanisms that shorten battery lifetimes in electric vehicles and grid storage systems. Conventional density functional theory (DFT) struggles with scalability and accuracy when mapping such pathways. Quantum algorithms can potentially achieve higher accuracy at reduced computational cost. By targeting ≤18 qubits, ≤5 reaction steps, and runtime ≤700 seconds, the project ensures feasibility on near-term simulators and backends.

The project will deliver a turnkey Jupyter notebook pipeline that:

Generates ethylene glycol + O₂ system Hamiltonians along the oxidation pathway,

Applies QSD to extract ground and transition states,

Benchmarks energy barriers against classical references, and

Visualizes reaction coordinate profiles for end-user interpretation.

This project sits at the intersection of quantum chemistry, algorithms, and industry-driven applications, providing mentees with hands-on experience in applying Qiskit to real-world challenges in energy and sustainability.

Deliverables
Primary Deliverables:
The project will deliver a turnkey Jupyter notebook pipeline that:-

Qiskit-based Jupyter notebook implementing QSD reaction-coordinate tracing for ethylene glycol oxidation
Benchmarking of transition state energies against classical baselines (e.g., PySCF, Gaussian DFT)
Visualization tool (matplotlib/plotly) showing the reaction coordinate with energy barriers highlighted
Documentation of methodology, including error analysis, runtime profiling, and industry relevance
Minimal Viable Product (MVP):

Working prototype notebook that computes at least one transition state for the oxidation pathway with QSD and compares it to a classical calculation
MENTOR
Name: Rishab Ghosh
GitHub: https://github.com/RishabGhosh98
Linkedin https://www.linkedin.com/in/rishab-ghosh-160985141/
What I do: I am an Engineer working in Quantum Computing with experience in Information Security at Infosys Center of Emerging Technology and Sciences with a background in Computer Science Engineering and research experience in quantum computing, quantum machine learning, and unconventional computing architectures. I have presented quantum research (e.g., Quantum-based Self-Attention Neural Networks for NLP at BQIT 2021) and participated in hackathons like MIT iQuHACK, Yale–Stanford QCHack, and IBM/Challenges and QWorld events. My expertise spans computational modeling, hybrid classical–quantum algorithms, and optimization for NP-hard problems.

My recent focus is on applying Qiskit Nature and quantum algorithms to model real-world challenges in battery degradation, energy storage, and materials optimization, with the goal of bridging industrial R&D pipelines to near-term quantum solutions

Goals:

Gain hands-on expertise in quantum chemistry simulations with Qiskit.

Learn to implement and optimize QSD algorithms for transition-state mapping.

Develop skills in scientific visualization and benchmarking for industrially relevant problems.

Additional Information:

Time commitment: ~5–8 hours per week for 12 weeks.
Prerequisites: [Python + Jupyter notebooks
Basic Qiskit familiarity (quantum circuits, operators)

Background in chemistry (molecular orbitals, transition states) is helpful but not mandatory)

Resources: Google Colab or local Python environment with Qiskit installed
Optional HPC or GPU for benchmarking classical references]

Mentoring style:
My mentoring style emphasizes structured milestones, reproducibility, and clarity of scientific communication. I like to combine weekly syncs (Discord) with asynchronous code reviews on GitHub, ensuring progress is both measurable and flexible to the mentee’s pace.

Type of Mentees I am looking for

I am looking for a mentee who is curious, self-motivated, and willing to bridge domains. Ideally, they have:

Basic familiarity with Python and Jupyter notebooks.

Some exposure to quantum computing (Qiskit, variational algorithms, or Hamiltonian simulation).

An interest in chemistry, materials science, or energy sustainability applications.

Most importantly: an eagerness to learn iteratively and ask good questions.

You do not need to be an expert in quantum chemistry to join; curiosity and consistency are more important than depth.
