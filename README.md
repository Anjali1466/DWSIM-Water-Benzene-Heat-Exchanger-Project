# DWSIM Heat Exchanger Simulation – Water/Benzene

## Project Overview

This repository contains a DWSIM process simulation featuring a heat exchanger with water and benzene streams.

The uploaded `.dwxmz` file is the complete DWSIM simulation package. The model contains a heat exchanger, material streams, and thermodynamic/property information for the simulated system.

## Simulation Software

- DWSIM
- DWSIM Build Version: 9.0.5.0
- Operating system recorded in the simulation: Windows 11

## Main Unit Operation

**Heat Exchanger**

The simulation contains a DWSIM heat exchanger configured with:

- Counter-current flow
- Heat-exchange profile calculation enabled
- Shell-and-tube geometry information
- 1 shell in series
- 2 shell passes
- 50 tubes
- 2 tube passes per shell
- Tube length: 5 m
- Tube outside diameter: 60 mm
- Tube inside diameter: 50 mm

## Components

The simulation data contains:

- Water
- Benzene

## Engineering Concepts Demonstrated

- Heat exchanger modelling
- Counter-current heat transfer
- Energy balance
- Heat-transfer performance
- LMTD-based analysis
- Shell-and-tube heat exchanger configuration
- Process simulation
- Thermodynamic/property calculations

## Process Concept

```text
Hot / Cold Inlet Stream
          |
          v
   ┌───────────────┐
   │ HEAT EXCHANGER│
   │ Counter-current│
   └───────────────┘
          |
          v
    Outlet Streams
```

## Key Parameters Available in the Model

The DWSIM case includes heat-exchanger calculations such as:

- LMTD correction factor
- Heat-transfer performance
- Hot-side and cold-side Reynolds numbers
- Heat-exchanger geometry
- Flow direction
- Outlet vapour fractions
- Stream properties

## Repository Contents

```text
DWSIM-Water-Benzene-Heat-Exchanger-Project/
│
├── README.md
├── .gitignore
│
├── DWSIM_Files/
│   └── Water-Benzene_Heat_Exchanger.dwxmz
│
├── Results/
│   └── README.md
│
└── Documentation/
    └── README.md
```

## How to Open

1. Install a compatible version of DWSIM.
2. Open DWSIM.
3. Open the file:

`DWSIM_Files/Water-Benzene_Heat_Exchanger.dwxmz`

4. Inspect the flowsheet, streams, heat exchanger configuration, thermodynamic data, and calculated results.

## Results to Add

For a stronger engineering portfolio, add screenshots showing:

- Complete DWSIM flowsheet
- Heat exchanger configuration
- Hot and cold inlet conditions
- Hot and cold outlet conditions
- Heat duty
- LMTD
- Heat-transfer performance
- Stream property tables

## Chemical Engineering Relevance

This project demonstrates practical understanding of:

- Heat transfer
- Energy balances
- Process simulation
- Heat exchanger design concepts
- Shell-and-tube equipment
- Thermodynamics
- Fluid-flow parameters
- Process equipment modelling

## Author

**Eslavath Anjali**  
B.Tech Chemical Engineering, IIT Madras

## Disclaimer

This is an academic/portfolio simulation. The model and results should be checked in DWSIM before being used for engineering design or industrial decisions.
