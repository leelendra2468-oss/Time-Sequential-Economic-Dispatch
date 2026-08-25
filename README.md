# Impact of Uncertainty on Time-Sequential Economic Dispatch

## Overview
This repository contains the simulation models and dataset used to evaluate the impact of demand and renewable uncertainty on Day-Ahead (DA) scheduling and Real-Time (RT) Security-Constrained Economic Dispatch (SCED). The study examines real-time solver feasibility under varying net-load deviations ranging from -23% to +48%.

## Key Features
* **Time-Sequential Architecture:** Modeled DA scheduling followed by 5-minute RT SCED adjustments incorporating generator ramp rates and line limits.
* **Reserve Allocation Sensitivity:** Evaluated system feasibility across fixed spinning reserve margins (0%, 10%, 15%, and 50%).
* **Feasibility Analysis:** Demonstrated that static reserves cause dispatch infeasibility during high variance, highlighting the necessity of adaptive reserve strategies.

## Tools & Frameworks
* **Software:** AMES Power Market Simulator
* **Solver:** IBM ILOG CPLEX Optimization Studio
* **Modeling:** Pyomo / Python
