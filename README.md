# Modelling-Simulations
Modelling &amp; Simulations Coursework on SIR modelling of Zombie Outbreaks
Link to Course: https://github.com/fourier-space/Modelling-and-Simulation/tree/main

## Overview

This repository contains Jupyter notebooks and supporting materials for **Modelling and Simulations (DESE71019)** coursework. The project explores the dynamics of a fictional zombie outbreak using SIR (Susceptible-Infectious-Recovered) framework. The repository also introduces iterations of the model, such as the incorporation of a cure mechanism, non-dimensionalization, and bifurcation analysis, to understand the critical parameters governing the outbreak's behavior.

## Repository Contents

1. **SZR Cure Introduction Model.ipynb**  
   This is the **main** notebook which the numerical analysis shown in the report is based on. This includes the calculations and plots of the model with the introduction of cure.

2. **Basic Model.nb**  
   This is the analysis of the base SZR model. As this has been widely covered by many academic papers, the analysis of this model will not be extensive as the one shown in the .pynb file

3. **Cure Model (Final).nb**  
   This is the wolfram mathematica notebook for the SZR Cure Introduction Model. This include the animation for the time-series plot which was used to find the critical value of $\tau$.

## Key Features

- **Baseline SIR Model**: Study of the system dynamics without cure interventions.
- **Cure Mechanism**: Introduction of a Heaviside function to model cure delivery and its effects on the system.
- **Non-Dimensionalization and Bifurcation Analysis**: Understanding dominant terms and critical parameter values for system stability.
- **Numerical Analysis**: Visualizations of phase portraits, time-series plots, and sensitivity analyses using Python and Wolfram Mathematica.

## Installation

To run the notebooks, you need the following:

- Python (>= 3.8)
- Jupyter Notebook
- Required Python libraries: `numpy`, `sympy`, `matplotlib`, `scipy`, `copy`, and `ipywidgets`.

## How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/zombie-outbreak-modelling.git
   ```

2. Navigate to the directory:

   ```bash
   cd zombie-outbreak-modelling
   ```

3. Open the notebooks in Jupyter Notebook or JupyterLab:

   ```bash
   jupyter notebook
   ```

4. Execute the cells sequentially to replicate the results and gain insights into the system's dynamics.

## Key Results

- **Base Model**: Highlights the doomsday equilibrium as the dominant state unless swift human intervention occurs.
- **Cure Model**: Demonstrates the importance of cure delivery time (`τ`) and effectiveness (`γ`) in preventing a zombie takeover.
- **Lyapunov and Fractal Analysis**: Identifies chaotic behaviors and sensitivity to initial conditions, emphasizing critical thresholds for intervention.

## Acknowledgements

This coursework was completed as part of the **Modelling and Simulations (DESE71019)** module at **Imperial College London**. Special thanks to Dr. Freddie Page for their guidance.

## License

This repository is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this project with proper attribution.
