# MOSFET Simulation using Silvaco TCAD

This project involves the simulation and analysis of MOSFETs using **Silvaco ATLAS**, focusing on the impact of different channel materials — **Silicon (Si)**, **Germanium (Ge)**, and **Silicon-Germanium (SiGe)**. The primary goal was to compare the electrical characteristics, especially the **I-V (current-voltage)** behavior, of these MOSFETs and evaluate their performance.

## Objectives

- Design and simulate MOSFETs with different channel materials.
- Plot and analyze I-V characteristics for:
  - Si-MOSFET
  - Ge-MOSFET
  - SiGe-MOSFET
- Compare performance metrics such as drive current, threshold voltage, and subthreshold behavior.

## Tools Used

- **Silvaco TCAD (Atlas, DeckBuild, TonyPlot)** — for structure definition, simulation, and data visualization.
- **Python/Excel** — for additional graphing and comparative analysis (optional).

## Methodology

1. **Device Design**:
   - Created 2D MOSFET structures using standard parameters.
   - Defined doping profiles, oxide thickness, gate material, and mesh regions.

2. **Material Variation**:
   - Simulated each MOSFET structure with Si, Ge, and SiGe as the channel material.
   - Maintained identical geometry and doping for a fair comparison.

3. **Simulation**:
   - Ran DC simulations to extract the I-V characteristics.
   - Used `log` and `linear` scale plots for detailed analysis.

4. **Analysis**:
   - Plotted transfer and output characteristics for each device.
   - Compared threshold voltage (Vth), on-current (Ion), and subthreshold slope.

## Results

- **Ge-MOSFET** showed higher drive current due to higher carrier mobility but suffered from increased leakage.
- **SiGe-MOSFET** provided a balanced trade-off with improved current and manageable leakage.
- **Si-MOSFET** had lower performance but better stability and control.

## Repository Structure
