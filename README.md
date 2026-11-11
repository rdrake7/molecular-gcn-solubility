
# Molecular GCN Demonstration

A simple Graph Convolutional Network (GCN) implementation using PyTorch Geometric and RDKit.

## Overview

This project demonstrates molecular graph construction, GCN training, and evaluation using the ESOL aqueous solubility dataset (1,128 molecules).

## Implementation

- Convert SMILES into molecular graphs using RDKit
- Generate atom features using molecular descriptors
- Implement a two-layer GCN with global mean pooling
- Train using Adam and MSE loss
- Evaluate using RMSE, MAE, and R2

## Note

This is a demonstration of molecular GCN implementation. Hyperparameters have not been systematically optimized.

## References

**Delaney, J. S. (2004).** ESOL: Estimating Aqueous Solubility Directly from Molecular Structure.  
https://doi.org/10.1021/ci034243x

**Medina, H., Drake, R., & Farmer, C. (2025).** Accelerated prediction of molecular properties for per- and polyfluoroalkyl substances using graph neural networks with adjacency-free message passing.  
https://doi.org/10.1016/j.envpol.2025.126705
