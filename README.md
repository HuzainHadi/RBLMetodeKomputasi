# Underdamped Oscillator Analysis

This Python project explores the dynamics of an underdamped oscillator using numerical simulation and data visualization. The system is modeled using a second-order differential equation, and the simulation results are analyzed to understand the behavior of the oscillator.

## Project Structure

- **`code.ipynb`**: Jupyter Notebook containing the simulation code, analysis, and visualizations for the underdamped oscillator.
  
## Features

- **Numerical Simulation**: Solves the differential equation governing the underdamped oscillator using numerical methods.
- **Visualization**: Plots the time response of the oscillator to visualize underdamped behavior.
- **Parameter Exploration**: Allows users to explore the effects of different damping ratios and natural frequencies on the oscillator's response.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python packages (install using `pip`):
  - numpy
  - matplotlib
  - scipy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/underdamped-oscillator.git
   cd underdamped-oscillator
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook code.ipynb
   ```

## Usage

1. Launch the Jupyter Notebook and execute the cells sequentially to run the simulation and visualize the results.
2. Modify the parameters in the Notebook to observe how changes in damping ratio and natural frequency affect the system's behavior.

## Project Workflow

- **Initialization**: Define initial conditions and parameters for the oscillator.
- **Simulation**: Use `scipy.integrate.solve_ivp` to solve the differential equation.
- **Analysis**: Generate plots to analyze the displacement, velocity, and phase plot of the oscillator.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## Acknowledgments

This project was inspired by classical mechanics and control systems theory. Special thanks to the open-source community and ChatGPT for providing tools that make such simulations possible.
