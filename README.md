# Artificial Intelligence — Programming Homework, Spring 2025

> Course assignments for the **Artificial Intelligence** course at Sharif University of Technology, Spring 2025.  
> **Author:** Nasim Javdani · [GitHub](https://github.com/javdaninasim) · [LinkedIn](https://linkedin.com/in/nasim-javdani-810a9932a)

---

## Overview

This repository contains seven programming homework assignments (PHWs) covering the core topics of a university-level AI course. Each assignment is implemented in Python as a Jupyter Notebook, combining theoretical explanations with hands-on experimentation.

---

## Repository Structure

```
AI_PHW_Spring_2025/
├── AI_PHW_CSP_Spring_2025/                                        # HW: Constraint Satisfaction Problems
├── AI_PHW_HiddenMarkovModel_Spring_2025/                          # HW: Hidden Markov Models
├── AI_PHW_MachineLearning&Classification_Spring_2025/             # HW: ML & Classification
├── AI_PHW_Minimax_Spring_2025/                                    # HW: Minimax & Adversarial Search
├── AI_PHW_ModelingRobotNavigationUsingBayesianNetwork_Spring_2025/ # HW: Robot Navigation with Bayesian Networks
├── AI_PHW_NeuralNetworks_Spring_2025/                             # HW: Neural Networks
└── AI_PHW_ReinforcementLearning_Spring_2025/                      # HW: Reinforcement Learning
```

---

## Assignments

### `AI_PHW_CSP_Spring_2025/` — Constraint Satisfaction Problems
Formulating and solving CSPs using:
- Backtracking search with heuristics (MRV, degree, LCV)
- Arc consistency (AC-3)
- Applications: map coloring, N-Queens, scheduling

### `AI_PHW_HiddenMarkovModel_Spring_2025/` — Hidden Markov Models
Sequence modeling with HMMs:
- Forward algorithm (likelihood computation)
- Viterbi algorithm (most probable state sequence)
- Baum-Welch algorithm (parameter learning)

### `AI_PHW_MachineLearning&Classification_Spring_2025/` — ML & Classification
Supervised learning methods:
- k-Nearest Neighbors, Decision Trees, Naive Bayes
- Evaluation: accuracy, precision, recall, F1, confusion matrix

### `AI_PHW_Minimax_Spring_2025/` — Minimax & Adversarial Search
Game-tree search for two-player zero-sum games:
- Minimax algorithm
- Alpha-beta pruning
- Application: game agents (e.g., Tic-Tac-Toe, Connect Four)

### `AI_PHW_ModelingRobotNavigationUsingBayesianNetwork_Spring_2025/` — Robot Navigation via Bayesian Networks
Probabilistic inference for robot localization:
- Bayesian Network construction and variable elimination
- Belief propagation
- Modeling uncertainty in sensor readings and actions

### `AI_PHW_NeuralNetworks_Spring_2025/` — Neural Networks
From-scratch and framework-based implementation:
- Multi-layer perceptron (MLP) with backpropagation
- Activation functions, weight initialization, regularization
- Training and evaluation on benchmark datasets

### `AI_PHW_ReinforcementLearning_Spring_2025/` — Reinforcement Learning
Core RL algorithms:
- Q-Learning and SARSA
- Value iteration and policy iteration
- Grid-world environments and convergence analysis

---

## Technologies

| Tool | Purpose |
|---|---|
| Python 3 | Core programming language |
| Jupyter Notebook | Interactive development and reporting |
| NumPy / SciPy | Numerical computation |
| scikit-learn | ML utilities and evaluation |
| PyTorch / TensorFlow | Neural network implementation |
| Matplotlib | Visualization |

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/javdaninasim/AI_PHW_Spring_2025.git
   cd AI_PHW_Spring_2025
   ```
2. Install dependencies:
   ```bash
   pip install numpy scipy scikit-learn torch matplotlib jupyter
   ```
3. Open any assignment notebook:
   ```bash
   jupyter notebook
   ```

---

## Course Info

- **Course:** Artificial Intelligence (AI)
- **Institution:** Sharif University of Technology, Department of Computer Engineering
- **Presenter:** Mohammad Hossein Rohban
- **Semester:** Spring 2025
