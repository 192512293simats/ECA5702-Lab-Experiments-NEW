# ECA5702 -- Nanoelectronics and Devices

This repository contains the simulation and software-analysis
experiments for all **20 experiments** in the **ECA57 -- Nanoelectronics
Laboratory**. The experiments cover nanoparticle optics, quantum
confinement, nanoscale transistor architectures, carbon-based and 2D
materials, memory devices, spin-dependent transport, biosensors, quantum
transport, crystal characterization, and nanofabrication.

## Experiments

### 1. Simulation of Scattering and Absorption of Multi-Layer Sphere and Core--Shell Nanoparticles Using Mie-Plot

-   Models homogeneous, core--shell, and multilayer spherical
    nanoparticles.
-   Obtains extinction, scattering, and absorption efficiency spectra.
-   Identifies localized surface plasmon resonance (LSPR) and studies
    its shift with shell thickness.
-   Checks the energy balance between extinction, scattering, and
    absorption.

### 2. Particle Size Estimation Using Extinction Spectra by Mie-Plot

-   Generates extinction spectra for nanoparticles of different radii.
-   Extracts peak wavelength, peak extinction, and spectral width
    (FWHM).
-   Builds calibration curves between spectral features and particle
    radius.
-   Estimates an unknown particle size from its extinction spectrum.

### 3. Simulation of Density of States of Quantum Well Structure Using nanoHUB

-   Simulates the density of states (DOS) for quantum wells with
    different thicknesses.
-   Identifies quantized subband edges and the step-like 2D DOS.
-   Studies the effect of well width and effective mass on subband
    energies.
-   Compares the results with the infinite quantum-well model.

### 4. Simulation of Energy States of Quantum Dot Using nanoHUB

-   Simulates the allowed energy levels of quantum dots.
-   Examines how quantum confinement changes with dot size.
-   Compares energy states for the geometries specified in the
    experiment.
-   Relates discrete energy levels to nanoscale material behaviour.

### 5. MOSFET Scaling Analysis and Subthreshold Swing Calculation Using nanoHUB

-   Studies MOSFET characteristics as device dimensions are scaled.
-   Extracts and analyses subthreshold swing (SS).
-   Examines changes in drain current, leakage, and switching behaviour.
-   Relates short-channel effects to nanoscale MOSFET performance.

### 6. Simulation and Comparative Analysis of GAA-FET and Vertical MOSFET Characteristics Using nanoHUB

-   Simulates the electrical characteristics of GAA-FET and vertical
    MOSFET devices.
-   Examines current response under applied terminal voltages.
-   Compares the two transistor architectures.
-   Studies the influence of device geometry and gate control on
    performance.

### 7. Simulation of V--I Characteristics of Multi-Gate FinFET Using nanoHUB

-   Simulates the voltage--current characteristics of a multi-gate
    FinFET.
-   Studies drain-current variation with gate and drain bias.
-   Examines the electrical response under the specified operating
    conditions.
-   Relates multi-gate control to improved channel electrostatics.

### 8. Simulation of Single-Electron Transistor (SET) and Tunnel FET Characteristics Using nanoHUB

-   Studies the operating principles of SET and Tunnel FET devices.
-   Examines single-electron effects and band-to-band tunnelling.
-   Observes and compares the simulated electrical characteristics.
-   Discusses their relevance to low-power nanoscale electronics.

### 9. Band Structure Simulation for Graphene and Carbon Nanotubes Using nanoHUB

-   Simulates the electronic band structures of graphene and carbon
    nanotubes.
-   Examines energy bands, band gaps, and electronic states.
-   Compares metallic and semiconducting behaviour where applicable.
-   Relates band structure to possible electronic-device applications.

### 10. Simulation of Electronic Transport Characteristics in CNTFET and GFET Using nanoHUB

-   Simulates transport characteristics of carbon-nanotube FETs and
    graphene FETs.
-   Studies the effect of gate voltage on drain current.
-   Compares the electrical response of CNTFET and GFET devices.
-   Relates carbon-based channel materials to nanoscale transistor
    operation.

### 11. Simulation and Comparative Study of Transition Metal Dichalcogenide FETs and 2D Heterostructure Interfaces

-   Studies transistor behaviour using 2D transition-metal
    dichalcogenide (TMD) materials.
-   Examines transfer characteristics and field-effect mobility.
-   Compares band alignment at 2D heterostructure interfaces, including
    type-I, type-II, and type-III alignments.
-   Discusses the potential of atomically thin channels for scaled
    transistors.

### 12. Phase Identification and Quantitative Phase Analysis of Multi-Phase Nanomaterials Using FullProf

-   Identifies crystalline phases from powder X-ray diffraction (XRD)
    patterns.
-   Uses FullProf for whole-pattern Rietveld refinement of multiphase
    samples.
-   Determines phase weight fractions, lattice parameters, and
    crystallite size.
-   Evaluates refinement quality using agreement factors such as Rwp and
    χ².

### 13. Memory Device Modeling: RRAM, PCM and FeRAM Using nanoHUB

-   Models three non-volatile memory technologies: resistive RAM (RRAM),
    phase-change memory (PCM), and ferroelectric RAM (FeRAM).
-   Identifies SET/RESET behaviour and high-/low-resistance states in
    RRAM.
-   Studies resistance changes with programming pulses in PCM.
-   Analyses polarization--electric-field hysteresis and compares memory
    characteristics.

### 14. Simulation of Tunneling Magnetoresistance (TMR) by Varying Barrier Height Using nanoHUB

-   Models spin-dependent electron transport through a magnetic tunnel
    junction.
-   Studies tunnelling magnetoresistance for different barrier heights.
-   Compares parallel and antiparallel magnetic configurations.
-   Relates barrier properties and spin-dependent transmission to TMR
    response.

### 15. Biosensor and Bio-FET Characteristics Using nanoHUB

-   Studies the operation of biosensors and Bio-FET structures.
-   Examines how biochemical surface interactions influence electrical
    characteristics.
-   Analyses transfer-curve changes and sensor response.
-   Relates device sensitivity to the sensing layer and operating
    conditions.

### 16. Calculation of Potential of a pH Sensor Using nanoHUB

-   Calculates the surface potential response of a pH-sensitive sensor.
-   Studies the effect of pH and electrolyte conditions on sensor
    potential.
-   Compares SiO₂ and Ta₂O₅ sensing films and their sensitivity.
-   Examines pH-dependent Bio-FET transfer-curve shifts and
    salt-concentration effects.

### 17. Kronig--Penney Model and Band Structure Analysis Using nanoHUB

-   Models electrons in a one-dimensional periodic potential.
-   Obtains allowed and forbidden energy bands and the E--k relation.
-   Determines band edges, band gaps, and effective mass from band
    curvature.
-   Studies how barrier height and width influence the band structure.

### 18. Demonstration and Analysis of Quantum Tunneling Using nanoHUB

-   Simulates electron transmission through a potential barrier.
-   Plots transmission probability against electron energy.
-   Examines below-barrier tunnelling and above-barrier transmission.
-   Studies resonant tunnelling in a double-barrier structure and
    compares it with a single barrier.

### 19. Rietveld Refinement and Lattice Parameter / Carrier Concentration Determination Using FullProf

-   Prepares powder XRD data and a FullProf refinement control file.
-   Performs staged Rietveld refinement of structural and profile
    parameters.
-   Determines lattice parameters, unit-cell volume, crystallite size,
    and refinement indicators.
-   Estimates dopant/carrier concentration from refined occupancy and
    discusses the need for Hall-effect validation.

### 20. Nanofabrication Process and Atomistic Simulation Study: EUV/E-Beam/Nanoimprint, CVD/ALD/PVD, Etching/CMP and nanoHUB

-   Compares EUV, electron-beam, and nanoimprint lithography using
    resolution and depth-of-focus calculations.
-   Studies deposition methods: CVD, ALD, and PVD; calculates ALD film
    growth.
-   Calculates etch depth, etch selectivity, and CMP removal rate.
-   Simulates argon-ion impact on a silicon surface and analyses sputter
    yield and radial distribution function (RDF).

## Tools and Requirements

-   **Mie-Plot** for nanoparticle scattering, absorption, extinction
    spectra, and particle-size estimation.
-   **nanoHUB** account and access to the relevant simulation tools for
    quantum structures, transistor devices, band structures, transport,
    memory devices, sensors, tunnelling, and atomistic simulation.
-   **FullProf Suite** (including WinPLOTR and EdPCR where required) for
    XRD phase analysis and Rietveld refinement.
-   A modern web browser and a stable internet connection for online
    simulation platforms.
-   **MATLAB, Python, Excel, or Origin** may be used for additional
    calculations, plotting, and data analysis where specified by the lab
    manual.
-   Input datasets, crystallographic information files (CIFs),
    instrument-resolution data, or other experiment-specific files may
    be required.

Tool names, availability, and interfaces may change. Follow the
procedure and settings specified in the laboratory manual for each
experiment.

## How to Use This Repository

1.  Open the folder for the experiment you want to perform.
2.  Read the corresponding experiment procedure in the lab manual.
3.  Install or open the required software or online simulation tool.
4.  Enter the specified material properties, dimensions, bias
    conditions, wavelength ranges, or other parameters.
5.  Run the simulation or analysis and inspect the generated plots and
    numerical results.
6.  Record the required values, calculations, and observations in the
    lab record.
7.  Compare the results with the expected physical trends and reference
    calculations in the manual.
8.  Save relevant plots, output files, and analysis notes in the
    corresponding experiment folder.

## Repository Contents

-   Experiment folders for the 20 laboratory experiments.
-   Simulation setups, analysis files, scripts, and output graphs where
    included.
-   The laboratory manual containing experiment procedures, input
    parameters, and expected outcomes.
-   Supporting datasets or reference files where provided.

The exact files available for each experiment depend on the contents of
its corresponding folder. The experiment descriptions above summarize
the scope of the laboratory manual and do not imply that every
experiment folder contains executable code or completed simulation
outputs.

## Author

**Lokesh A (192512293)**\
B.E. Electronics and Communication Engineering (ECE)

## Subject

**ECA5702 -- Nanoelectronics and Devices**
