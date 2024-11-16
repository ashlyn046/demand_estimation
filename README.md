# Demand Estimation Project

## Overview
This Demand Estimation Project encompasses two specialized subprojects, `ml_estim` and `berry_demand`. Each of these projects simulates demand and estimates parameters using different methods. 

## Subprojects

### ml_estim
**Flight Demand Estimation using Maximum Likelihood Estimation (MLE)**
- **Purpose**: Simulates flight demand and estimates parameters for a logistic demand model.
- **Key Features**:
  - Generates synthetic data using Poisson distributions.
  - Computes partial derivatives of the likelihood function.
  - Optimizes parameters (`alpha` and `delta`) with SciPy's `minimize`.
  - Visualizes objective and log-likelihood surfaces through 3D plots.
- **Read More**: [ml_estim/README.md](ml_estim/README.md)

### berry_demand
**Product Demand Estimation using IV and OLS Regression**
- **Purpose**: Simulates product demand and prices, estimates market shares, and calculates demand parameters.
- **Key Features**:
  - Generates synthetic data for demand estimation, including product characteristics and prices.
  - Implements three demand sampling methods: Custom Discrete, Cumulative Sum, and Uniform distributions.
  - Estimates price sensitivity and product characteristic effects using IV and OLS regression.
  - Utilizes multiprocessing for efficient parallel computations.
- **Read More**: [berry_demand/README.md](berry_demand/README.md)

For detailed information on each subproject, refer to their respective README files in the `ml_estim` and `berry_demand` directories.