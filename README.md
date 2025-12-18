# Swiggy Route Optimization using Reinforcement Learning

## Overview
This project explores how **Reinforcement Learning (RL)** can be applied to improve **food delivery route optimization**, inspired by Swiggy’s real-world delivery challenges.

Current delivery systems largely rely on **greedy, ETA-based routing**, which works well locally but often fails to optimize **long-term efficiency**, especially under dynamic conditions such as traffic fluctuations, unpredictable order inflow, and batching constraints.

Through this project, I model the delivery routing problem as a **Markov Decision Process (MDP)** and demonstrate how RL-based agents can learn **adaptive, long-term routing strategies** using a simplified **Grid World environment**.

---

## Problem Statement
How can a food delivery platform dynamically assign delivery routes to agents in real time to maximize:
- Delivery efficiency  
- On-time performance  
- Customer satisfaction  

while accounting for:
- Traffic uncertainty  
- Order deadlines  
- Future delivery opportunities  

---

## Motivation
Traditional greedy routing approaches:
- Assign the nearest available agent immediately  
- Ignore future orders and traffic variations  
- Use rigid rules (e.g., fixed order limits per trip)  
- Do not learn from historical outcomes  

This can lead to **globally suboptimal routes**, even if each local de
