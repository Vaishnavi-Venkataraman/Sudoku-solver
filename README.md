# **Sudoku Solver**

The Sudoku Solver project implements an efficient _backtracking_ algorithm for solving Sudoku puzzles, integrating advanced data structures for constraint management and visualization. 
The core of the solution relies on a _graph-based representation_ of the Sudoku grid, where cells are treated as vertices and constraints (row, column, and 3x3 block) are modeled as edges between them.
To optimize the solving process, the algorithm uses a _Minimum Remaining Values (MRV) heuristic_ implemented via a _heap_ (priority queue) to prioritize cells with the fewest valid options, reducing the search space and improving efficiency.

Additionally, the solver provides dynamic visualization of the puzzle-solving process using _NetworkX_ for graph representation and _Matplotlib_ for plotting the Sudoku grid.
The backtracking algorithm is enhanced with real-time visualization of each step, displaying the placement of numbers and the evolving state of the puzzle using _Vertex Coloring_ concept.
The code also allows for custom puzzle input from the user or generates random puzzles with varying difficulty.

This project combines fundamental algorithms with practical data structures, offering a visually engaging and computationally efficient approach to solving and understanding Sudoku puzzles.
