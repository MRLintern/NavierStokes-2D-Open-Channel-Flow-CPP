# NavierStokes-2D-Open-Channel-Flow-CPP

## Introduction
* This is a __Modern C++__ version of the [NavierStokes-2D-Open-Channel-Flow Fortran Solver](https://github.com/MRLintern/NavierStokes-2D-Open-Channel-Flow). 
* The __2D Navier-Stokes Equations__ are discretisised via the __Finite Volume Method__. 
* The __Velocity__ and __Pressure__ matrices are solved via the __Gauss-Seidel__ Iterative Method with __Red-Black Ordering__ to help accelerate __convergence__.
* An __implicit time integration scheme__ is also used.
* Note: utilising __Red-Black Ordering__ will allow us to __parallelise__ the solver with e.g. __OpenMP__
* The resulting data (`.dat/.csv`) will be plotted via a `Python script`. I will also attempt to make an `animation` of the __Velocity__ and __Pressure__ fields.

## Requirements
* Compiler: `g++ 13.3.1`.
* Developed on `Linux (Ubuntu 20.04)`.
* Developed with `Sublime Text`.
* `CMake`.
* `Python 3.7.6` for running the `visualisation script`.
* `matplotlib`, `pandas`, `NumPy` and `ffmpeg`.
* `Eigen Template Library`.

## Model 
* TODO
## Getting and Running the Software
* TODO
