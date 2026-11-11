# Multi-Drone Tactical Tracking and Simulation Framework

A software-based multi-drone tracking and simulation project exploring aerial surveillance, geometric target localization, state estimation, telemetry analysis, and coordinated multi-agent simulation.

## Project Overview

This project explores a modular software framework for modelling multi-drone environments and studying tracking and coordination concepts through simulation.

The work combines mathematical geometry, state estimation, visualization, and data analysis to represent drone movement and system states in a simulated environment.

## Key Areas

- Multi-agent drone swarm simulation.
- Geometric localization using triangulation.
- Particle-filter-based state estimation.
- Trajectory visualization and tracking analysis.
- Simulation telemetry generation and Excel reporting.
- Coverage-planning experiments.
- Multi-agent coordination concepts.

*This repository describes software simulation and research work. It does not establish physical deployment, operational capability, or field validation.*

## Repository Structure

```text
DRDO-Drone-Swarm-System/
│
├── src/
│   ├── enemyswarm.py
│   ├── enemy_swarm.py
│   ├── tethered_triangulation.py
│   ├── particle_filter.py
│   ├── 10v10_swarmfight.py
│   ├── tethered_triangulation_visualizer.py
│   └── coverage_hcp_kruskal.py
│
├── data/
│   └── Sanitized input data and configuration
│
├── results/
│   └── Approved, non-sensitive simulation outputs
│
├── dashboard/
│   └── Approved visualization images
│
├── documentation/
│   └── Technical documentation
│
├── requirements.txt
├── .gitignore
└── README.md
```

## Technology Stack

- Python
- NumPy
- Pandas
- Matplotlib
- OpenPyXL
- Scientific computing and data visualization

## Project Components

### 1. Multi-Agent Simulation
Simulation of multiple aerial agents and their movement through a virtual environment.

### 2. Geometric Localization
Study of geometric reconstruction and triangulation methods for estimating spatial positions.

### 3. State Estimation
Particle-filter-based estimation and visualization of uncertain system states.

### 4. Telemetry and Analysis
Generation of structured simulation data, trajectory records, and analytical spreadsheets.

### 5. Coverage Planning
Exploration of spatial coverage and graph-based planning concepts.

## Installation

Clone the repository:

```bash
git clone YOUR_PRIVATE_REPOSITORY_URL
cd DRDO-Drone-Swarm-System
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Activate it on Linux/macOS:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Project

Individual scripts can be executed from the project root after reviewing their input requirements and configuration:

```bash
python src/enemyswarm.py
```

```bash
python src/particle_filter.py
```

```bash
python src/tethered_triangulation_visualizer.py
```

Some modules may require input datasets or additional configuration. Refer to the documentation before execution.

## Project Scope and Limitations

- Results are based on software simulations and available experimental data.
- Simulation outputs should not be interpreted as real-world flight performance.
- Localization accuracy depends on the assumptions and geometry used in each experiment.
- Hardware integration and physical deployment should only be claimed where independently verified.
- Public repository contents must exclude restricted, confidential, or personally identifiable information.

## Project Status

Software modules, simulation experiments, visualizations, and analytical outputs are being organized into a documented repository.

Further documentation and approved results will be added as the repository is prepared for portfolio presentation.