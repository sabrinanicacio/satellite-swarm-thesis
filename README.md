# Satellite Swarm Reconfiguration: Fuel-Optimal and Fault-Tolerant Control

This repository contains the full MATLAB simulation suite developed for my senior thesis at Princeton University, titled:

**“Fuel-Optimal Dynamic Reconfiguration Algorithms for Satellite Swarms in LEO”**

## 🚀 Overview

The project explores fuel-efficient trajectory planning and distributed control strategies for satellite swarms operating in low Earth orbit (LEO). It focuses on scalable, autonomous reconfiguration under realistic conditions including:

- Drift-based triggering logic
- Fault-tolerant leader failure
- Initial state perturbations
- Collision avoidance under nonlinear dynamics
- Optimization with convex (CVX) and nonlinear (fmincon) solvers

All simulations are conducted in the LVLH frame using Clohessy-Wiltshire dynamics and tested against parameters from NASA's Starling mission.

---

## 📊 Simulations Included

| Simulation | Description |
|------------|-------------|
| SIM 01     | Passive baseline drift using CW equations |
| SIM 02     | Event-triggered agent selection logic |
| SIM 03     | Controlled vs. passive follower trajectories |
| SIM 04     | Full five-agent reconfiguration in Starling orbit |
| SIM 05     | Leader failure and fault-aware reconfiguration |
| SIM 06     | Initial velocity perturbation robustness |
| SIM 07     | Nonlinear repulsion-based collision avoidance (failed) |
| SIM 08     | Nonlinear optimization with hard safety constraints (infeasible) |

---

## 📌 Requirements

- MATLAB R2023a or later
- CVX Toolbox (for convex optimization): [cvxr.com/cvx](http://cvxr.com/cvx)
- Optimization Toolbox (for `fmincon`)

---

## 🔬 Citation

If you use this work for your own research or teaching, please cite:

@thesis{nicacio2025swarm, author = {Sabrina Nicacio}, title = {Fuel-Optimal Dynamic Reconfiguration Algorithms for Satellite Swarms in LEO}, school = {Princeton University}, year = {2025} }

---

## 🔗 Contact

Sabrina Nicacio  
Mechanical and Aerospace Engineering  
Princeton University  
Incoming graduate student at Stanford University
snicacio@stanford.edu  
