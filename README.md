![Sudoku Solver Example](/sedoku_image.PNG "Sudoku Solver")

# Sudoku Solver - Python Implementation

## Overview
This Python-based Sudoku Solver is designed to tackle any standard 9x9 Sudoku puzzle. Useing backtracking algorithm, it fills in missing digits in a Sudoku grid.

## Requirements
- Python 3.x

## Installation
Simply download the script and execute it with Python.

## Usage
1. **Define Your Sudoku Puzzle**: 
   The puzzle is represented in a 9x9 grid, with zeros marking empty spaces. Adapt the `board` variable to match your puzzle.

   Example:
   ```python
   board = [
       [7, 8, 0, 4, 0, 0, 1, 2, 0],
       [6, 0, 0, 0, 7, 5, 0, 0, 9],
       ...
   ]
   ```

2. **Execute the Solver**:
   Run the script. It will initially display the original board, proceed to solve the puzzle, and finally, present the completed board.

   Command:
   ```
   python sudoku_solver.py
   ```

3. **Output**: 
   The script outputs the initial Sudoku board with its empty spaces, followed by the solved version.

## Functions
- `solve(bo)`: The primary function for solving the Sudoku puzzle.
- `valid(bo, num, pos)`: Validates whether a number's placement adheres to Sudoku rules.
- `print_board(bo)`: Elegantly prints the Sudoku board.
- `find_empty(bo)`: Locates the next vacant spot on the board.

## Limitations
- The script is tailored for standard 9x9 Sudoku puzzles.
- Unsolvable puzzles will lead to the re-display of the original board.

## License
This project is freely available under the [MIT license](https://opensource.org/licenses/MIT). You are welcome to use, modify, and distribute the code as per your requirements.



For additional inquiries or issues, feel free to initiate a discussion in the project's repository.
