Compressible Flow Calculator

This Python library is for compressible flow calculations, including
normal shocks, oblique shocks, and Prandtl–Meyer expansions. It also includes a diamond-shaped airfoil example for lift and drag estimation.

This project started as a single script for a project in my Aerodynamics course which has now been refactored into a clean, testable, and reusable Python package.

![CI](https://github.com/zrmaile/Compressible-Flow/actions/workflows/ci.yml/badge.svg)

---

## Here are the features of the calculator...

- Normal shock relations
- Oblique shock (θ–β–M) solver
- Prandtl–Meyer expansion fans
- Diamond airfoil pressure distribution
- Lift and drag coefficients for supersonic flow
- Example scripts and automated tests

---

## Here are assumptions made by the calculator...

- Ideal gas
- Constant ratio of specific heats (γ = 1.4 by default)
- Inviscid, 2D flow
- Small-angle diamond airfoil model

This code is not intended for high-fidelity CFD.
