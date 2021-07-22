# A-Search
A * algorithm is a type of search algorithm that seeks the shortest path between the beginning and end states. It is used in a variety of applications, including maps.  The A* method is used in maps to compute the shortest distance between the source (starting point) and the destination (final state).

The A* algorithm includes three parameters:

g :  The cost of travelling from the original cell to the current cell is denoted by g. Essentially, it is the total of all the cells visited since leaving the initial cell.
h : the estimated cost of travelling from the present cell to the end cell, also known as the heuristic value. The true cost cannot be determined until the last cell is reached. As a result, h is the estimated cost. We must make certain that the expense is never overestimated.
f : it is the sum of g and h. So, f = g + h

The algorithm takes choices by taking the f-value into consideration. The algorithm travels to the cell with the least f-value. This process is repeated until the algorithm reaches its target cell.

