# Sudoku Solver
![SolverImg](https://github.com/joelb429078/SudokuSolver/assets/160978621/51002182-73f2-41f9-aaa9-b3f72e75c13b)


## Overview

This project is an efficient Sudoku solver implemented in Python. Sudoku is a popular logic-based number puzzle consisting of a 9x9 grid divided into nine 3x3 subgrids. The objective is to fill the empty cells with numbers from 1 to 9, ensuring each number appears exactly once in each row, column, and 3x3 subgrid.

## Features

- **High Efficiency**: The solver is optimised for speed and can solve even the hardest Sudoku puzzles, such as Arto Inkala's Sudoku, in just 0.36 seconds.
- **Advanced Algorithm**: Utilises constraint satisfaction with backtracking and constraint propagation.
- **Comprehensive Testing**: Includes a variety of sample Sudoku puzzles for thorough validation.

## Implementation Details

The solver employs a combination of advanced techniques to achieve high performance:

1. **Grid Representation**: Uses a 9x9 matrix where zeros represent empty cells.
2. **Constraint Propagation**: Reduces the search space by eliminating impossible values for each cell.
3. **Backtracking Search**: Recursively attempts to fill the grid, backtracking upon encountering constraint violations.
4. **Optimisation**: Enhanced with forward-checking and the Minimum Remaining Value heuristic for improved efficiency.

## Getting Started

### Prerequisites

- Python 3.x
- NumPy library

### Installation

Clone the repository and navigate to the project directory:

```sh
git clone https://github.com/joelb429078/SudokuSolver.git
cd sudoku-solver
```

### Usage
To use the Sudoku solver, run the Jupyter Notebook provided in the repository:
```sh
jupyter notebook sudoku.ipynb
```

Follow the instructions in the notebook to input your Sudoku puzzle and see the solution.

### Testing
The notebook includes a set of sample Sudoku puzzles of varying difficulty. You can run these tests to validate the solver's performance and correctness.

### Performance
The solver's efficiency is demonstrated by its ability to solve Arto Inkala's hardest Sudoku puzzle in just 0.36 seconds. This is achieved through a well-implemented combination of constraint satisfaction and optimisation techniques.

### License
This project is licensed under the MIT License.

