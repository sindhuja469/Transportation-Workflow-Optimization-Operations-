
# Transportation & Workflow Optimization Model

## Overview
This project implements a **Transportation Optimization Model** using **Linear Programming** to minimize total production and shipping costs while satisfying supply, demand, and capacity constraints. The model reflects a real-world logistics planning scenario involving multiple plants, destinations, and route costs.

The solution supports **route efficiency, capacity utilization, and cost optimization**, which are critical objectives in logistics and operations management.

---

## Business Problem
A company operates multiple production plants supplying goods to several destinations.  
Key challenges include:
- Balancing **total supply and demand**
- Allocating shipments efficiently across routes
- Minimizing combined **production and transportation costs**
- Managing **excess capacity** when supply exceeds demand

---

## Methodology
- Formulated the problem as a **Transportation Linear Programming (LP) model**
- Introduced a **dummy destination** to balance excess supply
- Defined:
  - Decision variables for shipment quantities
  - Supply and demand constraints
  - Cost-minimization objective function
- Solved the optimization using the **lpSolve** package in R
- Interpreted results using operational and economic insights

---

## Tools & Technologies
- **R**
- **lpSolve** (Linear Programming)
- **ggplot2** (Visualization)
- **R Markdown**

---

## Key Features
- Route optimization under capacity and demand constraints  
- Cost minimization with real-world logistics assumptions  
- Analysis of shipment patterns and unused capacity  
- Dual formulation for economic interpretation of routing decisions  

---

## Results
- Successfully optimized shipment allocation across plants and destinations
- Achieved a **minimum total cost of 55,320**
- Identified:
  - Optimal shipment quantities per route
  - Efficient use of plant capacities
  - Non-profitable routes eliminated by the model

---

## Practical Applications
This model can be applied to:
- Logistics and transportation planning  
- Route design and optimization  
- Capacity planning and utilization analysis  
- Cost reduction initiatives in supply chain operations  

---

## How to Run
1. Install required packages:
```r
install.packages("lpSolve")
install.packages("ggplot2")
