# Simulation of Projectile Motion with Wind Influence

This project simulates the motion of a projectile launched from the ground towards the north, incorporating the effects of gravity and air resistance, as well as the influence of wind from different directions. The simulation utilizes Euler's method to numerically solve the equations of motion and generates both 2D and 3D visualizations of the projectile's trajectory.

## Project Components

### 1. Importing Libraries
We begin by importing the necessary libraries:
- `matplotlib`: For plotting and visualizations.
- `numpy`: For numerical operations.
- `mpl_toolkits.mplot3d`: For 3D plotting.
- `IPython.display`: For updating plots in Jupyter notebooks.

### 2. ProjectileTrajectory Class
The core of the project is the `ProjectileTrajectory` class, which models the trajectory of the projectile. It contains the following components:

#### a. Initialization (`__init__` method)
The class is initialized with several parameters:
- `mass`: Mass of the projectile (kg).
- `initial_speed`: Initial speed of the projectile (m/s).
- `angle`: Launch angle in degrees.
- `diameter`: Diameter of the projectile (m).
- `time_step`: Time step for the simulation.
- `wind_speed`: Speed of the wind (default is 0).
- `gravity`: Gravitational constant (default is 9.8 m/s²).
- `drag_coeff`: Drag coefficient (default is 0.47 for a sphere).
- `air_density`: Density of air (default is 1.2 kg/m³).
- `wind_dir`: Direction of the wind (1 - S to N, 2 - E to W, 3 - N to S, 4 - W to E).

#### b. Calculating Trajectory (`get_trajectory` method)
This method computes the trajectory of the projectile using Euler's method. It:
- Initializes velocity and position components.
- Computes drag force due to initial speed and wind.
- Updates acceleration components based on wind direction.
- Iteratively updates the position and velocity of the projectile until it hits the ground.

#### c. 2D Animation (`animation_2d` method)
This method generates a 2D animation of the projectile's trajectory:
- Iterates through each time step.
- Updates the plot every 4th frame or on the last frame.
- Clears the previous output and pauses briefly to create an animation effect.

#### d. 3D Animation (`animation_3d` method)
This method generates a 3D animation of the projectile's trajectory:
- Iterates through each time step.
- Updates the plot every 4th frame or on the last frame.
- Clears the previous output ande 3D animation
projectile.animation_3d(pos_x, pos_y, pos_z, time)
