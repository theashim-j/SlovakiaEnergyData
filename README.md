## This project was done under the MSc in Energy Systems Course partial fulfilment requirement. 

# SlovakiaEnergyData
Data and code related to the modelling of energy transition of Slovak republic.

# 🇸🇰 Slovakia Energy Transition Analysis (LEAP + Power Flow)

This repository provides the complete dataset and codebase used for analyzing Slovakia’s energy transition using LEAP ( Low Emissions Analysis Platform) and Python-based power flow simulations.

## Contents

- `data/` – Time-series energy data (2000–2050) covering fuel consumption, electricity demand, emissions and sectoral breakdowns for Baseline, Policy (POL) and Net-Zero (NET) scenarios.
- `leap_outputs/` – Processed outputs from LEAP scenario modelling.
- `powerflow/` – Python scripts using Pandapower to simulate Slovakia’s transmission network: load flow, line losses, voltage levels and bus topology.

## Methodology

1. **LEAP Modeling**: Energy demand projections for residential, commercial, transport, industry and power sectors under three scenarios.
2. **Fuel & Emissions Analysis**: Aggregated and disaggregated projections for electricity, coal, oil, gas, biofuels and emissions pathways.
3. **Power Flow Analysis**: Simulation of line flows, bus voltages and reactive losses using real geospatial and technical network parameters via Pandapower.

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/slovakia-energy-transition.git
    cd slovakia-energy-transition
    ```

2. To run power flow analysis:
    ```bash
    cd powerflow
    python run_powerflow.py
    ```

3. LEAP data is included for reference and visualization.

## License

This project is licensed under the [MIT License](LICENSE).

