# CFD-Solver-Development-for-External-and-Internal-Flow-
Developed custom MATLAB solvers to simulate internal laminar pipe flow across Reynolds numbers (Re = 100, 400, 2000) using both the Finite Difference Method (FDM) and Lattice Boltzmann Method (LBM), comparing them on accuracy, stability, and runtime
Implemented an explicit FDM scheme in MATLAB using staggered grids, central differencing, and Successive Over-Relaxation (SOR) to solve the pressure Poisson equation, achieving near second-order spatial convergence
Coded a D2Q9 LBM solver with bounce-back boundary conditions and equilibrium distribution functions, carefully tuning relaxation parameters for stability and validating performance against ANSYS Fluent results 
Demonstrated that the LBM solver achieved 2.8× faster runtime (89.59s vs. 252.83s) while closely matching Fluent results, showcasing its suitability for efficient CFD simulations in low- to mid-Re regimes
Analyzed centerline velocity profiles and x-velocity contours to capture boundary layer growth, flattening of profiles with Re, and local conservation behaviors — reinforcing fundamental fluid mechanics through numerics
