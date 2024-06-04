# Large Amount of Particles Simulation

This repository contains a simulation program written in Python and Cython that simulates the behavior of individual particles in a 2-dimensional pipe. The pipe contains a fluid, and the profile of the fluid flow follows a sinusoidal pattern.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

The `large_amount_of_particles.ipynb` program simulates the movement of particles within a 2D pipe. The fluid within the pipe flows with a sinusoidal velocity profile, adding complexity to the simulation.

## Features

- Simulates particle dynamics in a 2D environment.
- Fluid flow with a sinusoidal profile.
- High performance through the use of Cython.

## Technologies

- **Python**: The primary language for the simulation logic.
- **Cython**: Used to accelerate the performance-critical parts of the simulation.

## Installation

To run the simulation, you need to have Python and Cython installed on your machine. Follow these steps to set up the environment:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/large_amount_of_particles.git
    cd large_amount_of_particles
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Compile the Cython code:
    ```bash
    python setup.py build_ext --inplace
    ```

## Usage

Open the Jupyter notebook `large_amount_of_particles.ipynb` to run the simulation. You can launch Jupyter Notebook from the command line:

```bash
jupyter notebook large_amount_of_particles.ipynb
