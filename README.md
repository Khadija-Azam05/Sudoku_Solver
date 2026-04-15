# 🧩 Sudoku Solver using CSP (Backtracking + AC-3)

## 📌 Introduction
This project is a Sudoku solver based on the concept of **Constraint Satisfaction Problem (CSP)**.  
It solves 9×9 Sudoku puzzles using **Backtracking Search**, **Forward Checking**, and **AC-3 algorithm**.

---

## ⚙️ CSP Representation
- **Variables:** 81 cells (A1 to I9)  
- **Domains:** Numbers 1–9  
- **Constraints:** No repeated numbers in any row, column, or 3×3 box  

---

## 🧠 Methods Used
- **Backtracking Search:** Tries values recursively and backtracks on failure  
- **Forward Checking:** Removes invalid values early after assignment  
- **AC-3 Algorithm:** Enforces arc consistency before and during search  
- **MRV Heuristic:** Selects the cell with the fewest possible values  

---

## 📊 Results & Discussion
The solver was tested on four puzzles: **easy, medium, hard, and very hard**.

- **Easy:** Solved quickly with minimal backtracking  
- **Medium:** Required moderate backtracking  
- **Hard:** Required significant search and failures  
- **Very Hard:** Heavily dependent on backtracking  

👉 As difficulty increases, backtracking calls and failures increase, while AC-3 becomes less effective alone.

---

## 🎯 Conclusion
This project demonstrates that Sudoku can be efficiently solved using CSP techniques.  
Backtracking ensures correctness, while AC-3 reduces unnecessary search, making it much faster than brute-force methods.


