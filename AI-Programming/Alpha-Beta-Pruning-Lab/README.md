# Lab 06: Alpha-Beta Pruning Optimization

## 📌 Overview
This lab implements the **Alpha-Beta Pruning** optimization for the Minimax algorithm. By eliminating branches that do not affect the final outcome, the algorithm significantly reduces the search space in game trees.

This lab is part of the **AI-Programming** module for Semester IV.

## 🎯 Objectives
- Optimize the standard Minimax algorithm with `alpha` and `beta` parameters.
- Implement pruning logic: `if beta <= alpha: break`.
- Maintain the original recursive structure while improving efficiency.

## 💻 Implementation
The solution is developed in Python using a recursive approach to evaluate a game tree of depth 3.

### Core Logic:
* **Maximizing:** Updates `alpha` and prunes if it meets or exceeds `beta`.
* **Minimizing:** Updates `beta` and prunes if it is less than or equal to `alpha`.

## 📸 Lab Evidence

### Algorithm Execution
![Terminal Output](screenshots/output.png)
* Final optimal value calculated by the pruned Minimax algorithm.*

### Code Logic Screenshot
![Code Snippet](screenshots/code_logic.png)
* Implementation of the pruning conditions within the recursive calls.*

---
**Course:** BSAI Semester IV (Spring 2026)  
**Student:** Yasir Ahmed  
**Enrollment:** [02-136242-041]