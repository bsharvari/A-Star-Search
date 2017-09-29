# A-Star-Search
2D grid implementation of A-star algorithm, for optimal path planning

The grid is a 2D matrix (list) that has 1 where there are obstaces and 0 everywhere else.
The init and goal variables give the initial and final position of the robot, in the form of [x, y]
The heuristic is generally the distance the of each cell from the goal position. Here it is the cost of reaching the goal from every cell.

The A-star generates the shortest path to the goal based on the obstacles in the grid and the value in the heuristic matrix. The algorithm is efficient since it avoids unnecessary expansion of all the cells, and only looking at the cells close to the optimal path.
