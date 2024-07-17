# Rat-in-a-Maze-Using-Backtracking
Implement a algorithm such that Rat should find a way to reach the destination and it should be optimal path with cost effectiveness using C Graphics

# Introduction
The Rat Maze algorithm is a pathfinding algorithm used to solve mazes by navigating through the maze cells to reach the destination. This algorithm utilizes a depth-first search approach with backtracking to find a feasible path from the starting point to the destination in a maze.

# Algorithm Overview
The rat_maze function in this repository is designed to solve a maze represented by a matrix. The algorithm uses a stack data structure to keep track of visited cells and backtracks when necessary.

# Procedure Steps
Initialize variables and necessary data structures.
Define possible moves in the maze matrix.
Mark cells in the maze as visited.
Start exploring the maze using a while loop until the destination is reached or no solution is found.
Check possible moves in the maze:
If a valid move is available and not visited, proceed to the next cell.
If the destination is reached, print "Goal Reached" and exit the loop.
If no valid move is available, backtrack to the previous cell.
Print the path taken by the algorithm.
If the maze has no solution, print "Solution does not exist".

# Output

WHITE- BACKTRACKING

PURPLE-PATH

GREEN-BLOCKS

YELLOW – START AND DESTINATION


![image](https://github.com/KAVINT21/Rat-in-a-Maze-Using-Backtracking/assets/95117554/345f900f-a934-4f57-af2a-5249996b262b)
