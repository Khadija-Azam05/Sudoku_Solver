🧩 Sudoku Solver using CSP (Backtracking + AC-3)
📌 Introduction

This project is a Sudoku solver based on Constraint Satisfaction Problem (CSP).
It solves 9×9 Sudoku puzzles using Backtracking Search, Forward Checking, and AC-3 algorithm.

⚙️ CSP Representation
Variables: 81 cells (A1–I9)
Domains: Numbers 1–9
Constraints: No repetition in rows, columns, or 3×3 boxes

🧠 Methods Used
Backtracking: Tries values and backtracks on failure
Forward Checking: Removes invalid values early
AC-3: Improves efficiency using constraint propagation
MRV Heuristic: Chooses cell with fewest options first

📊 Results & Discussion
The solver was tested on four puzzles: easy, medium, hard, and very hard.

Easy: Solved with minimal backtracking
Medium: Moderate backtracking required
Hard: High search and failures
Very Hard: Heavy dependency on backtracking

👉 As difficulty increases, backtracking calls and failures increase, while AC-3 becomes less effective alone.

🎯 Conclusion
This project shows that Sudoku can be efficiently solved using CSP techniques.
Backtracking ensures correctness, and AC-3 reduces unnecessary search, making the solver faster than brute-force methods.
