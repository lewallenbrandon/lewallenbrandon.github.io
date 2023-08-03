---
title: "Machine Learning - Randomized Optimization"
excerpt: "Random Forest classification algorithm implemented with Python, Pandas, and NumPy to predict, buy, sell, and hold
opportunities for stock market data. (From scratch; no Scikit-Learn)"
collection: portfolio
---

## Assignment 2: Randomized Optimization - Algorithm Analysis and Neural Network Performance

**I. Introduction:**
The study evaluates five optimization algorithms: Gradient Descent, Simulated Annealing, Genetic Algorithms, Random Hill Climbing, and MIMIC. The goal is to explore their performance across three problems (8-Queens, Flip Flop, Max k-Color) and their impact on a neural network predicting breast cancer presence.

**II. Problems Overview:**
1. **8-Queens:** Placing 8 Queen chess pieces on a board without attacks.
2. **Flip Flop:** Alternating bit strings with minimum repeating bits.
3. **Max k-Color:** Coloring nodes in a graph to minimize same-colored adjacent nodes.

**III. Algorithm Analysis Across Problems:**
- **Random Hill Climbing (RHC):** Balanced results, struggles with larger problem sizes.
- **Simulated Annealing (SA):** Reaches global optima, slower than expected.
- **Genetic Algorithms (GA):** Consistently obtains global optima, faster than expected.
- **MIMIC:** Slow but robust, fewer iterations for optimal fitness.

**IV. Algorithm Analysis on Neural Network:**
- **Gradient Descent (GD):** Performs well on scaled data, struggles without scaling.
- **Random Hill Climbing (RHC):** Improved performance with grid search, data scaling impacts negatively.
- **Simulated Annealing (SA):** Grid search improves results, scaling has mixed impact.
- **Genetic Algorithms (GA):** Best out-of-box, improved by scaling.
- **Conclusion:** Scaling affects algorithms differently, further investigation needed.

**V. Conclusion and Areas for Improvement:**
- **Algorithms:** Right algorithm for right problem, development time consideration.
- **Dataset:** Dataset structure may influence results, more explorations needed.
- **Neural Network:** Hyperparameter interaction with optimization methods and architectures require further study.
- **Scaling:** Scaling impact varies across algorithms and datasets, more strategies to explore.

**References:** Cited sources for algorithms, problems, and dataset.
