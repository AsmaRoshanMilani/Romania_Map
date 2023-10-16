# Romania_Map
This project is about implementing search algorithms (specifically UCS and  A*) for path finding problems on Romania map
![Screenshot 2023-10-08 121353](https://github.com/AsmaRoshanMilani/Romania_Map/assets/135136956/d6a34a85-2ef4-43a5-bc82-89feae7a1bca)
![Screenshot 2023-10-08 121406](https://github.com/AsmaRoshanMilani/Romania_Map/assets/135136956/be8ed6c5-e826-42a9-85f9-f345b4ce213b)
# Algorithms
• Uniform-Cost Search Algorithms:
Uniform-Cost Search is similar to Dijikstra’s algorithm. In this algorithm from the starting state, we will visit the adjacent states and will choose the least costly state then we will choose the next least costly state from the all un-visited and adjacent states of the visited states, in this way we will try to reach the goal state (note we won’t continue the path through a goal state ), even if we reach the goal state we will continue searching for other possible paths( if there are multiple goals). We will keep a priority queue that will give the least costly next state from all the adjacent states of visited states.
\n• A* Search Algorithm:
A* Search algorithm is one of the best and popular technique used in path-finding and graph traversals.One major practical drawback is its space complexity, as it stores all generated nodes in memory.

\n Uniform-cost expanded in all directions
A* expands mainly toward the goal, but does ensure optimality
