# sudokuSolver
 Solve any solvable sudoku board using a backtracking algorithm
## How to use the solver
To use the solver, assign the elements to a variable (let's say board) in the format of a list of list such that the blanks on the board are represented by zero and the element is represented by the number itself.

Example
```
board = [
    [7,8,0,4,0,0,1,2,0],
    [6,0,0,0,7,5,0,0,9],
    [0,0,0,6,0,1,0,7,8],
    [0,0,7,0,4,0,2,6,0],
    [0,0,1,0,5,0,9,3,0],
    [9,0,4,0,6,0,0,0,5],
    [0,7,0,3,0,0,0,1,2],
    [1,2,0,0,0,7,4,0,0],
    [0,4,9,2,0,6,0,0,7]]
```

Then use the `solve(board)` function to get the answers of the sudoku
