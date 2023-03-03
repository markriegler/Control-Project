# Control-Project
Control Project for VU Optimization with PDE Constraints (TU Vienna)

This project is a boundary control problem for the Poisson equation as a PDE constraint. It uses NGSolve for solving the PDEs.

The numerical optimization algoritms are:

- Conditioned Gradient method
- Projected Gradient method

## Overview

`/data/` contains the iterations' cost functional, its derivative and the chosen stepsizes as `.csv`-files.
`/plots/` contains plots which were produced by the postprocessing and the Juypter notebooks of the methods
`ConditionedGradient.ipynb` and `ProjectedGradient.ipynb` contain the optimization problems
  - The main parameters to be tweaked are located in cell [5]. `case` determines which examples/parameter configureations to be run.
