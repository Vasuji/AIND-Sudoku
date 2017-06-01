
# Sudoku

Sudoku is one of the world's most popular puzzles. It consists of a 9x9 grid, and the objective is to fill the grid with digits in such a way that each row, each column, and each of the 9 principal 3x3 subsquares contains all of the digits from 1 to 9.   The main goal of this project is to build an intelligent agent that will solve every sudoku while introducing  two powerful techniques that are used throughout the field of AI:

### ● Constraint Propagation:
There are some local constraints to each square. These constraints help to narrow the possibilities for the answer, which can be very helpful. We extract the maximum information out of these constraints in order to get closer to the solution. It shows how we can repeatedly apply simple constraints to iteratively narrow the search space of possible solutions. Constraint propagation can be used to solve a variety of problems such as calendar scheduling, and cryptographic puzzles.
### ● Search: 
When we get to the point where two or more possibilities are available, search comes in to play. What do we do? What if we branch out and consider both of them? Maybe one of them will lead us to a position in which three or more possibilities are available. Then, we can branch out again. At the end, we can create a whole tree of possibilities and find ways to traverse the tree until we find our solution. This is an example of how search can be used.

### ● Software used: Python, Tensorflow, Karas, Pygame
