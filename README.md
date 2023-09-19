# N-Body Simulation using Quadtree and Octree (Barnes-Hut Approximation)

Welcome to the N-Body Simulation project, which uses the Barnes-Hut approximation technique to simulate the interactions of N particles in a gravitational field. This simulation leverages both the Quadtree and Octree data structures for efficient computation.

## Overview

The N-Body Simulation is a classic problem in computational physics and computer graphics, often used to model phenomena like galaxies, star clusters, and molecular dynamics. This project offers an efficient approach using the Barnes-Hut approximation, which reduces the computational complexity from O(N^2) to O(N log N).

## Features

- **Barnes-Hut Approximation**: The Barnes-Hut algorithm is employed to approximate the gravitational forces between distant particles, significantly improving simulation efficiency.

- **Quadtree and Octree**: The simulation utilizes both Quadtree and Octree data structures, allowing for hierarchical partitioning and efficient neighbor searching.

- **Customizable Parameters**: You can customize simulation parameters, including the number of particles, simulation duration, time step, and more.

## Getting Started

To run the N-Body Simulation:

1. Clone this repository to your local machine.
2. Install the required dependencies (if any) specified in the project's documentation.
3. Compile and execute the simulation program.
4. Explore the simulated behavior of particles under gravitational forces.

## Usage

Here's a basic example of how to use the simulation:

```bash
# Compile the simulation (provide compilation instructions if necessary)
$ make
