# Lattice Boltzmann Method for Fluid Dynamics Simulation

This repository contains a Python implementation of the Lattice Boltzmann Method (LBM) for simulating fluid flows. The LBM is a computational technique used to model fluid dynamics at mesoscopic scales, offering advantages such as simplicity of implementation, scalability, and suitability for complex geometries.

## Overview

The Lattice Boltzmann Method represents the fluid as a collection of particles moving and interacting on a lattice grid. Instead of solving the Navier-Stokes equations directly, the method simulates the evolution of particle distribution functions, approximating fluid properties such as density and velocity.

## Implementation Details

The Python code in this repository implements the LBM for simulating fluid flows in a two-dimensional domain. It includes the following components:

- **Update Function**: Updates the particle distribution functions based on collision and propagation steps.
- **Fluid Properties Calculation**: Computes fluid density and velocity from the particle distribution functions.
- **Boundary Conditions Handling**: Implements various boundary conditions for physical boundaries and obstacles.
- **Visualization**: Provides visualization of fluid flow patterns and dynamic phenomena over time.

## Usage

To use the code:

1. Clone the repository to your local machine.
2. Install the required dependencies (NumPy, Matplotlib).
3. Run the main script (`main.py`) to execute the simulation with default or user-defined parameters.

## Simulation Results

The simulation generates visualizations depicting fluid flow patterns, interactions with boundaries, and dynamic phenomena. By analyzing the results, users can gain insights into complex fluid systems and phenomena.

## Contributions

Contributions to the project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Introduction to the Lattice Boltzmann Method](https://doi.org/10.1016/S0378-4754(97)00112-3)
- [Python Programming and Numerical Methods](https://doi.org/10.1007/978-3-030-28532-8)
