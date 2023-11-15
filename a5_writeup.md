# Assignment 5 Write up

Assignment 5 can be broken up into the following parts:
1. Import the Necessary Modules:
- `copy`: For creating deep copies of objects
- `Stack` and `Queue`: Custom implementations for DFS and BFS operations
2. Utility Functions: 
- `remove_if_exists`: Removes a specified element from a list if it exists, which is used to remove the possibilites from a cell
3. Board Class:
- Represents the Sudoku board
- Consists of functions that will find the most constrained cell, and update the board, which eliminates possible solutions
4. DFS & BFS Functions:
- `DFS`: Uses depth-first search to solve the Sudoku puzzle. It works by trying to fill the most constrained cell with potential values until a solution is found or backtracks if a mistake is made
- `BFS`: Uses breadth-first search to solve the Sudoku puzzle in a similar fashion to DFS but explores nodes level by level
5. Main Execution:
- Defines two different sets of initial moves for Sudoku puzzles
- Uses both DFS and BFS to solve each puzzle and prints the results


After completing the assignment, answer the following reflection questions:

## Reflection Questions

1. How do the performance and efficiency of the Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms compare when solving Sudoku puzzles? In what scenarios might one approach be preferable over the other?

The DFS is more effeinent than BFS in most cinerios. DFS is more effient in sudoku, only needing around 300 iterations in DFS while closer to 500 iterations in BFS for board 2. 

2. How did the choice of data structures (like the Stack for DFS and Queue for BFS) impact the implementation and functionality of the algorithms? Are there alternative data structures or design patterns that could have been used to achieve the same objectives?

The biggest way these data structued solved the puzzle is on effientiy. You could have an agorthim that randmized which board to solve out each time there was a guess, or you could have made a board that looks at how many numbers a selection would get rid of and base youe next board guess of that. DFS is just liekly more ffient. 

3. Considering the current implementation, how might the Sudoku solver be adapted or extended for larger puzzles or different types of grid-based logic games? How can the lessons learned from this assignment be applied to real-world problem-solving or optimization challenges?

You could easily adapt it changing a few functions and numbers here and there. The algorithims could still be used for not one-path-step-by-step games. These aglorthism are also likely more effient than most in most cinerios including logic based games. This could be used for optimization in completx equations where you need to generate multiple vlaues and check thier accuracy of equations. This is implemntlaed and could be implemtned in many differnet areas o the owrld. 
