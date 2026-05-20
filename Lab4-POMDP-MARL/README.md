# Lab 4: POMDP and Multi-Agent RL

This repository contains two Jupyter Notebooks covering advanced topics in Reinforcement Learning: **Partially Observable Markov Decision Processes (POMDPs)** and **Multi-Agent Reinforcement Learning (MARL)**.

## Notebooks Overview

### 1. POMDP.ipynb
This notebook introduces the fundamentals of planning under uncertainty using a POMDP framework. Key concepts covered include:
* **Belief MDPs:** Understanding how to translate partially observable states into a continuous belief space.
* **Belief Updating:** Implementing Bayes' Rule to update beliefs after taking actions and receiving noisy observations.
* **Value Iteration for POMDPs:** Calculating 1-step and 2-step expected returns, and demonstrating that the optimal value function over belief space is Piecewise Linear and Convex (PWLC).
* **Exact Value Iteration:** Working with $\alpha$-vectors to prune dominated strategies and fixing a Bellman backup bug in an exact POMDP Value Iteration solver.

### 2. MARL.ipynb
This notebook explores multi-agent cooperation in a grid-world Predator-Prey environment. Key concepts covered include:
* **Joint-Action Tabular Q-Learning:** Implementing a centralized learner and observing the exponential explosion of the state-action space ($O(|A|^N)$).
* **Independent Q-Learning (IQL):** Decentralizing the learning process where each agent learns its own policy. Discusses the challenges of non-stationarity and the violation of the Markov assumption due to concurrent exploration.
* **Hysteretic Q-Learning:** Addressing the underestimation bias of IQL by using asymmetric learning rates (a higher $\alpha$ for positive TD-errors and a lower $\beta$ for negative TD-errors) to "forgive" penalties caused by teammates' random exploration.

## Running on Google Colab

You can run the Jupyter Notebooks directly on [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index). Click on the badges below to open each notebook.

| **COMP64202** | **Lab Session** | **Google Colab Link** |
|---------------|-----------------|-----------------------|
| Apr 2, 2025   | POMDP           | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mingfeisun/COMP64202-RL/blob/master/Labs/Lab4-POMDP-MARL/POMDP.ipynb) |
| Apr 2, 2025   | MARL            | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mingfeisun/COMP64202-RL/blob/master/Labs/Lab4-POMDP-MARL/MARL.ipynb) |

## Saving Your Work
If you would like to save your changes from within Colab, you must save them before quitting. You can use the `File` menu to save the modified notebook either to Google Drive (`File → Save a copy in Drive`) or back to GitHub (`File → Save a copy to GitHub`). To save a Colab notebook to GitHub requires giving Colab permission to push the commit to your repository.