# **SIMULATION OF LOTKA-VOLTERRA SYSTEM WITH SEVERAL POPULATIONS**

This project presents a comprehensive numerical study of the **generalized Lotka-Volterra (LV)** equations, which are widely used in ecological modeling to describe the dynamics of interacting species in a population. The study explores how different ecological parameters and species interactions shape long-term population behavior across diverse communities.
It was created as a project for the course in *Stochastic Processes and Simluation in Natural Sciences*.

## 🧬 Project Overview

The generalized Lotka-Volterra model provides insights into how populations interact, including self-regulation, inter-species competition, and cooperative interactions. In this study, we:

- implement the Lotka-Volterra equations using Python and numerical integration;
- analyze how changing parameters such as growth rates and interaction coefficients affect the dynamics of populations;
- explore various systems with increasing complexity, ranging from two-species models to large eight-species networks.

## 📄 Structure

This notebook follows the outline:

1. **Theoretical Overview**  
   Formal description of the Lotka-Volterra equations and biological interpretations of the parameters.
   
2. **Numerical Implementation**  
   The LV model is numerically implemented using `scipy.integrate.solve_ivp`, with visualizations of time series, phase spaces, and stability analysis via the Jacobian matrix.

3. **Large-Scale Simulation Experiments**  
   A parameter sweep generates 20 independent systems under different ecological regimes, analyzing system dynamics, extinction count, Shannon diversity, and stability.
   
4. **Three-Species Dynamics**  
   Investigates fixed points, limit cycles, extinction, and invasion phenomena in 3-species models.
   
5. **Eight-Species Systems**  
   Scaling the model to 8 species, this section explores how parameter configurations affect diversity, dominance, and stability.

6. **Conclusion**  
   Summarizes the key findings and implications for ecological modeling using generalized Lotka-Volterra frameworks.

## 🔧 Tools & Technologies

- **Python** (NumPy, SciPy, Matplotlib)
- **scipy.integrate.solve_ivp** for numerical integration
- **Jacobian matrix analysis** for stability and dynamics assessment

## 🎯 Key Goals

- **Understand dynamics**: How species interactions (competition, predation, cooperation) shape population dynamics.
- **Parameter sensitivity**: Explore the impact of ecological parameters on the stability and diversity of species.
- **Simulation scalability**: Study the behavior of simple (2-species) and complex (8-species) ecosystems under varied conditions.
