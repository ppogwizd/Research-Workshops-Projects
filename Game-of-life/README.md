# Conway's Game of Life in Cython

This repository contains a Cython implementation of Conway's Game of Life, a cellular automaton simulation.

## Overview

Conway's Game of Life is a classic cellular automaton devised by the mathematician John Conway. It consists of a grid of cells that can be either alive or dead, and evolves according to simple rules based on the states of neighboring cells.

## Implementation Details

The Cython code in this repository implements Conway's Game of Life with optimizations for performance. It includes the following components:

- **Grid Representation**: Utilizes a two-dimensional grid to represent the cellular automaton.
- **Game Logic**: Implements the rules of Conway's Game of Life for updating cell states.
- **Cython Optimization**: Utilizes Cython to compile Python-like code into efficient C extensions, enhancing performance.

## Usage

To use the code:

1. Clone the repository to your local machine.
2. Install Cython and the required dependencies (NumPy).


## Simulation Results

The simulation generates visualizations depicting the evolution of the cellular automaton over time. Users can observe patterns such as gliders, oscillators, and stable configurations emerging from simple initial conditions.

## Contributions

Contributions to the project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.


## Acknowledgments

- [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)
- [Cython Documentation](https://cython.readthedocs.io/en/latest/)
