## Adsorption energy calculations using a toy calculator
A structural relaxation or structure optimization is the process of iteratively updating atom positions to find the atom positions that minimize the energy of the structure. Standard optimization methods are used in structural relaxations — below we use the Limited-Memory Broyden–Fletcher–Goldfarb–Shanno (LBFGS) algorithm. The step number, time, energy, and force max are printed at each optimization step. Each step is considered one example because it provides all the information we need to train models for the S2EF task and the entire set of steps is referred to as a trajectory. Visualizing intermediate structures or viewing the entire trajectory can be illuminating to understand what is physically happening and to look for problems in the simulation, especially when we run ML-driven relaxations.

## OUTPUT:

![WhatsApp Image 2024-10-19 at 12 07 07_f2b42014](https://github.com/user-attachments/assets/7f301a29-d837-420a-8754-eb54cb63d0fb)

