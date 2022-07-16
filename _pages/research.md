---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

# Research interets

1. High-order numerical methods for PDEs:
   - Finite element discontinuous Galerkin methods 
   - Finite difference/volume WENO methods
   - Spectral methods
2. Scientific computing:
   - Parallel implementation of numerical solvers
   - Efficient numerical algorithms

---


# Projects

## 1. Numerical simulation of plasma equilibrium evolution in nuclear fusion

*Undergraduate Research Program at USTC*

Supervisor: Prof. [Mengping Zhang](https://www.researchgate.net/profile/Mengping-Zhang)

July 2021 --- May 2022, USTC

The controlled nuclear fusion is one of the most prospective solution to the energy crisis and environmental problems. The tokamak has been widely investigated as the most feasible magnetically confined fusion device. Tearing mode instabilities have great influence on the fusion reaction thus worth stuying. In this research, in order to simulate the evolution process of tokamak plasma equilibrium numerically, we review different formulations of the MHD equations, select a suitable type of nonconservative resistive MHD that is based on perturbation and develop a parallel code using hybrid finite difference-Fourier pseudo spectral method in cylindrical coordinate. Using our code, we simulate the $(m,n)=(2,1)$ resistive tearing mode instability and compare the results against those obtained from the CLT and M3D-C1 code. The results fit well with the theory and our code exhibits satisfactory performance in maintaining numerical divergence of the magnetic field, fitting logrithmic growth rate of kinetic energy with resistivity, revealing mode structure independent of initial peturbation at the linear stage and reaching the final saturation stage.

Below is a plot of $\widetilde{E}_{\varphi}$ (the perturbation on the toroidal component of the electric field) at time $T=7000$, which reveals the resistive tearing mode structure and should be independent of the initial perturbation, and a log-plot of kinetic energy evlolution under different resistivity. Our code reveals the linear growing stage, mode structure and the logrithmic growth rate very well.

<img src="../files/cpt_14.png" width="50%"> <img src="../files/4energy.png" width="46%">



## 2. Positivity-preserving conservative low rank methods for Vlasov dynamics

Supervisor: Prof. [Xiangxiong Zhang](https://www.math.purdue.edu/~zhan1966/)
June 2022 --- present, Purdue U. (online)

The high-dimensionality of Vlasov dynamics makes it expenive to solve by traditional numerical methods. Utilizing the low-rank structure of the solution, people have developed cost-efficient methods using low-rank matrix approximation. However, very often a low-rank approximation of a given non-negative matrix (which corresponds to the solution) can have negative elements, resulting in non-physical solutions. In this research, our goal is to develop a positivity-preserving conservative low-rank method to solve this problem.