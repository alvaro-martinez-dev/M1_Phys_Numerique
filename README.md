# M1 Numerical Physics – Problem Sets

My solutions to the problem sets of the **Numerical Physics** course (M1, École Polytechnique), written in Python with Jupyter notebooks.

> **Credit:** the problem statements, the figures and the reference solutions were written by the course instructors. They are not my own work. My contribution is the code in the main notebook of each folder, where I solve the exercises.

## Contents

| Folder | Topic | What it covers |
|---|---|---|
| `L1_Numerov` | Numerov's method | Solving the stationary Schrödinger equation: bound states with the shooting method, asymptotic boundary conditions and quantum scattering |
| `L2_Ising` | 2D Ising model | Monte Carlo estimate of $\pi$, Metropolis algorithm, equilibration, physical averages and autocorrelation time |
| `L3_Cranck_Nicholson` | Advection–diffusion equations | Spectral method, finite differences with the Crank–Nicolson scheme, invading fronts and the complex Ginzburg–Landau equation |
| `L4_Hard_Disks` | Hard-disk collisions | Event-driven molecular dynamics: single disk, two-disk collisions, many disks and the approach to the Maxwell–Boltzmann distribution |

## Structure

Each folder follows the same layout:

```
LX_Topic/
├── projectX_topic.ipynb          # Problem statement + my solution
├── *.png / *.jpg                 # Figures used in the statement
└── Solution/
    └── projectX_topic_solution.ipynb   # Reference solution from the instructors
```

## Requirements

- Python 3
- Jupyter
- `numpy`, `scipy`, `matplotlib`, `tqdm`

## How to use

Open the notebooks with Jupyter Lab, Jupyter Notebook or VS Code. GitHub also shows them directly in the browser, including plots and equations.

If you are taking the course yourself, I recommend trying the exercises before looking at either my solutions or the reference ones.
