# 🧩 Sudoku Solver using CSP (Backtracking + AC-3)

## 📌 Introduction
This project solves a 9×9 Sudoku puzzle using **Constraint Satisfaction Problem (CSP)** techniques.  
It combines **Backtracking Search**, **Forward Checking**, and the **AC-3 algorithm** to efficiently find solutions.

---

## ⚙️ CSP Representation
- **Variables:** 81 cells (A1 to I9)  
- **Domains:** Numbers 1–9  
- **Constraints:** Each number must be unique in every row, column, and 3×3 box  

---

## 🧠 Techniques Used
- **Backtracking Search:** Recursively assigns values and backtracks on conflicts  
- **Forward Checking:** Eliminates invalid values after each assignment  
- **AC-3 Algorithm:** Enforces arc consistency to reduce search space  
- **MRV Heuristic:** Selects the variable with the minimum remaining values first  

---

## 📊 Results
The solver was tested on puzzles of different difficulty levels:

- **Easy:** Solved quickly with minimal backtracking  
- **Medium:** Required moderate backtracking  
- **Hard:** Needed deeper search and more backtracking  
- **Very Hard:** Heavily dependent on backtracking  

**Observation:**  
As difficulty increases, backtracking increases, while AC-3 alone becomes less effective.
