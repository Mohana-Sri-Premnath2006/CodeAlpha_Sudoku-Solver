
# 🧩 Sudoku Solver (C++)

A fast and efficient Sudoku Solver written in C++ using backtracking algorithm. This program takes a 9x9 Sudoku puzzle as input and solves it using recursive logic while ensuring all Sudoku rules are followed.

---

## 📖 Overview

This C++ project implements a classic Sudoku solver using a backtracking algorithm. It efficiently finds a solution for a partially-filled 9x9 Sudoku board by trying all possible combinations recursively and backtracking when a dead-end is reached.

---

## ✨ Features

- Solves any valid 9x9 Sudoku puzzle
- Uses efficient recursive backtracking
- Displays the solved puzzle on the console
- Validates input to prevent incorrect entries
- Modular, readable and beginner-friendly C++ code

---



## 📂 Resource List
C++ STL (Standard Template Library) – For basic I/O and data handling

G++ Compiler – To compile and run the C++ code

Code Editor or IDE – (e.g., Visual Studio Code, Code::Blocks, or Dev C++)

Terminal/Command Line – To execute the program




## ✅ Usage

This program allows users to solve any valid 9x9 Sudoku puzzle using a console-based interface.

1. Run the compiled program.
2. Enter the 9x9 Sudoku board row by row, using `0` for empty cells.
3. The program will attempt to solve the puzzle using backtracking.
4. If a solution exists, the complete solved board will be printed.
5. If no solution is possible, it will notify the user.

## ⚙️ How It Works

The Sudoku Solver uses the **backtracking algorithm**, which is a depth-first recursive approach:

1. It scans the board to find an empty cell (a cell with value 0).
2. It attempts to fill the cell with a number from 1 to 9.
3. For each number, it checks if the move is **valid**:
   - Number is not repeated in the current row.
   - Number is not repeated in the current column.
   - Number is not repeated in the 3x3 subgrid.
4. If valid, it fills the cell and moves to the next empty one recursively.
5. If none of the numbers fit, it **backtracks** to the previous cell and tries a different number.
6. The process continues until the board is solved or deemed unsolvable.

## 🔮 Future Enhancements

- 🔢 **Puzzle Generator**  
  Add functionality to generate random Sudoku puzzles of varying difficulty levels.

- 🧠 **AI Integration**  
  Integrate a heuristic-based solver for faster solving or visualization of strategies.

- 📄 **File Input/Output**  
  Allow input/output from and to text or CSV files.

- 🖼️ **GUI Support**  
  Build a graphical version using Qt or SFML for an enhanced user experience.

- 🌐 **Web App Version**  
  Convert to a web-based tool using WebAssembly (WASM) for browser execution.

- 🧪 **Unit Testing Suite**  
  Add tests to validate the solver logic and ensure robustness for edge cases.


## 📜 License

This project is open-source and available under the MIT License.


##  ✋🖐 Acknowledgement

I would like to express my sincere gratitude to the online programming community, documentation resources, and educators who helped me understand backtracking and problem-solving in C++.

This project was developed as part of my learning journey to strengthen my grasp of algorithms, recursion, and real-world applications of programming.

**Built with dedication and passion by [Mohana Sri Premnath].**

