# GridSentry – Power System Simulation & Security Analysis Tool

GridSentry is an interactive MATLAB App Designer application for simulating a 6-bus power system, performing N-1 contingency analysis, and visualizing renewable energy variability. It modernizes and expands on the functionality of a 2010 KU Leuven Master’s thesis by providing a clean, user-friendly interface and automated analysis tools.

## Features

- **6-Bus Power System Modeling**  
  Full generator, load, and transmission line configuration.

- **N-1 Contingency Analysis**  
  Automated outage simulation, recalculation, and result visualization.

- **Color-Coded Line Loading**  
  Highlights stressed lines (>85% loading) to support reliability assessment.

- **Renewable Integration Module**  
  Time-series simulation of a **150 MW solar farm** with interactive graphs and animated power variability.

- **Automated Reporting**  
  Export power flow results and analysis summaries in a structured format.

- **Standalone Deployment**  
  Compiled with MATLAB Compiler to run as a desktop application (no MATLAB license required).


## App Architecture

- **MATLAB App Designer** – User interface and visualization  
- **MATPOWER** – Power flow engine  
- **Custom MATLAB scripts** – Contingency simulation, solar modeling  
- **MATLAB Compiler** – Standalone installer generation  

## Repository Structure

GridSentry/
│── GridSentry.mlapp 
│── SecurityApp.prj 
│── README.md
│── .gitignore 
│── LICENSE
└── images/ # App screenshots 

