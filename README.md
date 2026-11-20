BIT 2118: Scientific Computing — Group & Individual Work Repository
Welcome to the official repository for BIT 2118 Scientific Computing. This repository contains Python-based implementations, modified real-world case studies, parameter variation analyses, and detailed documentation covering 20 core scientific computing tasks.
---
Course & Project Overview
Course Code & Title: BIT 2118 – Scientific Computing
Timeline: Group work to be completed by Week 10; Individual Group Project tasks conducted during Weeks 11–13.
Submission Policy: While discussions and conceptual planning are conducted collaboratively in groups, each student must maintain and submit their own individual GitHub repository. Group repositories are strictly prohibited. All links and documentation must be uploaded via VLMS.
---
Repository Structure
```text
BIT2118_Scientific_Computing/
│
├── README.md                      # Comprehensive project documentation (this file)
├── requirements.txt               # Python dependencies (NumPy, SciPy, Matplotlib)
│
├── code/                          # Base Python solution scripts for Tasks 2–20
│   ├── Task_02_numpy_arrays.py
│   ├── Task_03_vectorization.py
│   └── ...
│
├── changed_parameter/             # Scripts demonstrating parameter variation (Instruction C)
│   ├── Task_02_numpy_arrays_changed.py
│   └── ...
│
├── modified_case/                 # Scripts applying methods to new real-world cases (Instruction E)
│   ├── Task_02_water_tank_modified.py
│   └── ...
│
├── outputs/                       # Generated text logs, console outputs, and saved plots (.png)
│   └── ...
│
└── docs/                          # Detailed markdown documentation files per task
    └── ...
```
---
General Instructions Checklist
Every task implemented in this repository adheres strictly to the assessment guidelines:
Task Execution (Instruction A): All mandatory tasks (Tasks 2–20) are fully implemented.
Mathematical Identification (Instruction B): Input values, governing formulas, and numerical operations are explicitly documented.
Parameter Variation (Instruction C): At least one key input or parameter is systematically altered to analyze output sensitivity.
Interpretation (Instruction D): Outputs are explained in plain text, accompanied by graphical visualizations where applicable.
Real-World Modification (Instruction E): Programs are extended to solve distinct, practical real-world problems with documented assumptions and results.
Individual Submission (Instruction F): Maintained solely within this individual student repository.
---
Summary of Tasks & Mathematical Concepts
Task	Mathematical Concept & Python Module	Example Application / Real-World Problem
2	NumPy Arrays & Numerical Computation (`numpy`)	Sensor readings from IoT devices; batch temperature conversion.
3	Mathematical Functions & Vectorization (`numpy`, `timeit`)	Speed-up comparisons for large-scale network latency arrays.
4	Floating-Point Arithmetic & Errors (`numpy`)	Absolute/relative error quantification and catastrophic cancellation.
5	Matrix Algebra & Operations (`numpy`)	2D affine transformations (rotation and scaling) in computer graphics.
6	Systems of Linear Equations (`numpy.linalg`)	Resource allocation and solving $Ax = b$ for active server loads.
7	Gaussian Elimination & LU Decomposition (`scipy.linalg`)	Efficient repeated linear solves with single factorization $PA = LU$.
8	Iterative Methods (Jacobi & Gauss-Seidel)	Steady-state heat distribution across sparse grid networks.
9	Eigenvalues & Eigenvectors (`numpy.linalg`)	Network centrality metrics and PageRank-style analysis.
10	Root Finding: Bisection & Fixed-Point (`scipy.optimize`)	Thermal equilibrium temperature matching in non-linear systems.
11	Root Finding: Newton-Raphson & Secant (`scipy.optimize`)	Financial Internal Rate of Return (IRR) and Net Present Value (NPV).
12	Nonlinear Systems (`scipy.optimize.root`)	Intersection points between geometric curves (circle and parabola).
13	Interpolation (`scipy.interpolate`)	Cubic spline and linear interpolation for missing sensor data points.

14	Curve Fitting & Least Squares (`scipy.optimize.curve_fit`)	Empirical server response-time modeling under increasing user loads.
15	Numerical Differentiation (`numpy`)	Instantaneous velocity and acceleration estimation from GPS data.
16	Numerical Integration (`scipy.integrate`)	Smart-meter energy consumption via Trapezoidal and Simpson’s rules.
17	ODEs: Euler Method (`numpy`, `matplotlib`)	Newton's law of cooling for transient thermal simulation.
18	ODEs: SciPy Solvers (`scipy.integrate.solve_ivp`)	RC electrical circuit charging dynamics using adaptive step-size ODE solvers.
19	Numerical Optimization (`scipy.optimize.minimize`)	Cost minimization for cloud server resource allocation with constraints.
20	Monte Carlo Methods (`numpy.random`)	Probabilistic risk analysis and server overload simulation under uncertainty.
---
Getting Started & Installation
Prerequisites
Make sure you have Python 3.8 or higher installed on your system along with pip.
Installation Steps
Clone your individual repository:
```bash
   git clone <your-individual-github-repo-link>
   cd BIT2118_Scientific_Computing
   ```
Install the required Python packages:
```bash
   pip install -r requirements.txt
   ```
Running a Task Script
To execute any base task, navigate to the code directory or run from root:
```bash
python code/Task_02_numpy_arrays.py
```
To run a modified real-world case study:
```bash
python modified_case/Task_02_water_tank_modified.py
```
---
Python Libraries Used
NumPy (`np`): Fast vectorized array operations, linear algebra solvers, matrix products (`@`), and random number generation (`default_rng`).
SciPy (`scipy`): Advanced scientific computing submodules including `scipy.linalg`, `scipy.optimize`, `scipy.interpolate`, and `scipy.integrate`.
Matplotlib (`plt`): High-quality plot generation for visualizing convergence curves, fitted models, ODE trajectories, and simulation results.
Timeit (`timeit`): High-precision timing utilities for measuring the performance benefits of vectorization over explicit Python loops.
---
Key Mathematical Notation Reference
Throughout the documentation and individual task write-ups, scientific notation and mathematical equations are formulated using standard conventions:
Linear systems: $Ax = b$
Eigenvalue problems: $A \mathbf{v} = \lambda \mathbf{v}$
Numerical integration: $\int_{a}^{b} f(x) , dx$
Least squares objective: $\min \sum_{i=1}^{n} (y_i - \hat{y}_i)^2$
---
Author & Repository Maintenance
Student Name: Tymon Jasiri
Registration Number: [Your Reg Number Here]
Course: BIT 2118 Scientific Computing
Institution: [Your University/College Name]
