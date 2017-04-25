# A* maze solver
## Usage instructions
* Start Main, or open MazeSolver.jar (maze.txt gets generated in same folder)

## Implementation

* Input maze gets read from a file generated by the given maze generator

* The maze gets solved by the A* pathfinding algorithm. It is the most used algorithm, 
and one of the fastest algorithms to get the shortest path. It finds a path if it exists, and is guaranteed to be the shortest one.
By using a heuristic it gives the unchecked nodes an order to determine which has the priority to be checked first.
  * Comments in the AStar class!!!
  
## Examples
Randomly generated maze:

![Imgur](http://i.imgur.com/jziEuOa.png)

Solved maze with A*:

![Imgur](http://i.imgur.com/JJc8PcV.png)
