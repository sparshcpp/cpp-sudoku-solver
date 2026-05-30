# Sudoku Solver in C++
This project solves Sudoku puzzles using Backtracking Algorithm.
## Features
- Solves 9x9 Sudoku
- Uses recursion
- Backtracking approach
## Language
C++
## Concepts Used
- Recursion
- Backtracking
- Arrays
- STL Vector

## Project Workflow

1.Read the sudoku board
2.Find an empty cell represented by 0.
3.Try numbers from 1 to 9.
4.Validate the number using row, column, and 3x3 subgrid checks.
## Project Workflow

1. Read the Sudoku board.

2. Find an empty cell represented by 0.

3. Try numbers from 1 to 9.

4. Validate the number using row, column, and 3x3 subgrid checks.

5. Recursively solve the remaining cells.

6. Backtrack if a selected number does not lead to a valid solution.

## Function Overview

- isSafe() : Checks whether a number can be placed safely.

- solveSudokuRec() : Recursive backtracking function that solves the puzzle.

- solveSudoku() : Starts the solving process.

- main() : Initializes the Sudoku board and prints the solved output.
 

