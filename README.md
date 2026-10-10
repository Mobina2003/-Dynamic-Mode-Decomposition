# Optimal Control Analysis using Eigenvalues & DMD

## Overview
This repository contains a Python implementation and theoretical analysis of **Optimal Control Problems**. The project focuses on how eigenvalues and eigenvectors can be used to simplify, linearize, and solve complex control systems. It also explores **Dynamic Mode Decomposition (DMD)** as a powerful data-driven method for extracting linear dynamics from complex systems to facilitate optimal control.

## Key Topics Covered
- **Introduction to Optimal Control:** Understanding the cost function, system dynamics, and constraints.
- **Linearization:** Using Taylor Series expansion and Jacobian matrices around equilibrium points.
- **Equilibrium Points & Stability Analysis:** Analyzing system stability based on the sign of the real and imaginary parts of eigenvalues.
- **Dynamic Mode Decomposition (DMD):** Extracting dynamic modes from time-series data using Singular Value Decomposition (SVD) and regression.
- **Spectral Decomposition:** Decomposing large-scale coupled systems into simpler, decoupled subsystems for optimal control synthesis and solving decoupled Riccati equations.

## Technologies Used
- **Python 3.x**
- **NumPy** (Matrix operations and eigenvalue calculations)
- **Matplotlib** (Visualization of system stability, Taylor series approximations, and DMD predictions)
- **SciPy** (Linear algebra and SVD implementation)

