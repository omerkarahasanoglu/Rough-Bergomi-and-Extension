# Rough Bergomi Model Calibration and Piecewise Rough Bergomi Implementation

This repository contains the implementation and calibration of the **Rough Bergomi model** and its extensions, including the **Piecewise Rough Bergomi** approach. The work was conducted as part of a thesis project focused on modeling stochastic volatility with roughness features and calibrating these models to market data.

## Project Overview

- **Fractional Brownian Motion Simulation** is implemented to model the underlying volatility drivers.
- **Rough Bergomi model simulation** generates asset paths consistent with rough volatility.
- **Piecewise Rough Bergomi** and **Piecewise Fractional Brownian Motion** approaches extend the model to handle regime changes in the roughness (Hurst) parameter.
- **Calibration routines** use **Differential Evolution (DE)** and **Sequential Least Squares Programming (SLSQP)** to fit model parameters to market implied volatility data.
- **Implied Volatility Surface Construction and Comparison** evaluates model performance against market data.

---

## Repository Structure

- `fBm Simulation.ipynb` : Simulation of Fractional Brownian Motion (fBm) with configurable Hurst parameter **H**.
- `Rough Bergomi.ipynb` : Implementation of the standard Rough Bergomi model.
- `Piecewise Rough Bergomi.ipynb` : Extension of the rBergomi model to allow piecewise Hurst parameters.
- `Rough Bergomi Calibration with DE and SLSQP.ipynb` : Calibration routines combining global optimization (DE) with local refinement (SLSQP).
- `Implied Volatility Calculation and Comparison.ipynb` : Generates implied volatility surfaces from simulations and compares them with real market data.


## Thesis Information

**Thesis Name:** Modeling Rough Volatility with Regime Switching in the Rough Bergomi Framework
**Author:** Ömer Karahasanoğlu  
**Institution:** University of Edinburgh  
**Program:** Computational Mathematical Finance MSc  
**Year:** 2025


