# 🧩 Sudoku Solver (C++)

## 📌 Project Overview
This project is a **Sudoku Solver implemented in C++** using the **Backtracking algorithm**.  
The program automatically fills missing values in a 9×9 Sudoku grid while ensuring all Sudoku constraints are satisfied.

Empty cells are represented by `0`.

---

## ⚙️ Features
- Solves standard **9×9 Sudoku puzzles**
- Uses **recursive backtracking**
- Validates:
  - Row constraints
  - Column constraints
  - 3×3 subgrid constraints
- Displays both the **unsolved** and **solved** Sudoku grid

---

## 🛠️ Technologies Used
- **C++**
- **Backtracking Algorithm**
- **Recursion**

---

## 🧠 Algorithm Used
The algorithm follows these steps:
1. Find an empty cell in the grid.
2. Try placing numbers from **1 to 9**.
3. Check if the placement is safe according to Sudoku rules.
4. Recursively attempt to solve the rest of the grid.
5. If a conflict occurs, **backtrack** and try the next number.

---

## ▶️ How to Run the Program

### Step 1: Clone the Repository
```bash
git clone https://github.com/bangarparul88/Sudoku-Solver-CPP.git
