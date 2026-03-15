# Monte Carlo Pricing in a Hybrid Equity-Short Rate Model 📉🏦

## Overview
This project implements a sophisticated derivative pricing framework. Unlike the standard Black-Scholes model, which assumes constant interest rates, this project uses a **Hybrid Model** that combines:
1. **Equity Dynamics:** Geometric Brownian Motion (GBM) for the underlying stock price.
2. **Interest Rate Dynamics:** A Stochastic Short Rate model (e.g., Hull-White or Vasicek) to capture the term structure of interest rates.

## Key Features
* **Stochastic Modeling:** Implementation of correlated processes for stock prices ($S_t$) and interest rates ($r_t$).
* **Monte Carlo Simulation:** Large-scale simulations to estimate the fair value of European Call options.
* **Numerical Methods:** Discretization of SDEs (Stochastic Differential Equations) using Euler-Maruyama schemes.
* **Convergence Analysis:** Study of pricing accuracy relative to the number of simulation paths.

## Contents
* 📄 **[Technical_Paper_Hybrid_Model.pdf](./Technical_Paper_Hybrid_Model.pdf)**: Comprehensive report on model derivation, stochastic calculus framework, and numerical results.
* 💻 **[Monte_Carlo_Pricing_Implementation.ipynb](./Monte_Carlo_Pricing_Implementation.ipynb)**: Python code implementing the simulation engine and visualization.
* 📊 **[Project_Presentation.pdf](./Project_Presentation.pdf)**: Summary of the project methodology and key findings.

## Technical Stack
* **Language:** Python
* **Libraries:** NumPy (Vectorized simulations), Matplotlib, SciPy.
* **Mathematical Framework:** Stochastic Differential Equations, Monte Carlo Integration, Risk-Neutral Pricing.
