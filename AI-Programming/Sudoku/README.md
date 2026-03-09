# 🧩 Constraint Satisfaction Lab Task

**Name:** Yasir Ahmed  
**Enrollment:** 02-136242-041

---

## 📖 Project Overview
This repository contains a Python implementation of the **Map Coloring Problem**, a classic **Constraint Satisfaction Problem (CSP)**. The goal is to assign colors to various regions such that no two adjacent regions share the same color.

### 🗺️ Dataset
* **Regions:** `WA`, `NT`, `SA`, `Q`, `NSW`, `V`, `T`
* **Colors:** 🔴 Red, 🟢 Green, 🔵 Blue
* **Constraints:** Neighboring regions in the adjacency list must have different colors.

---

## ⚙️ Algorithm Logic
The solution uses a **Recursive Backtracking Algorithm**:

1.  **Validation:** The `is_valid` function checks if a color assignment conflicts with any neighbors.
2.  **Assignment:** It picks an unassigned region and attempts to assign an available color.
3.  **Recursion:** If the assignment is valid, it moves to the next region.
4.  **Backtrack:** If no valid color is found, it reverts to the previous state to try a different color.

---

## 🚀 How to Run
1.  Ensure you have a Jupyter environment installed (**VS Code** or **JupyterLab**).
2.  Open the file `Map Coloring.ipynb`.
3.  Run the cells to generate the solution.

---

## 📊 Output Example
```text
Map Coloring Solution:
WA  -> Red
NT  -> Green
SA  -> Blue
Q   -> Red
NSW -> Green
V   -> Red
T   -> Red