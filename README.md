## Shortest Path Finder
This Python project implements a Shortest Path Finder using the Breadth-First Search (BFS) algorithm to navigate through a maze. 
The maze is visualized using the curses library,
which provides a dynamic terminal interface where the algorithm's progress is displayed in real time.

## How It Works
The maze is a grid of characters, where:

"0" represents the start point.
"X" represents the end point (goal).
" " (spaces) are walkable paths.
"#" represents obstacles that block movement.

The program starts at the position of "0" and explores the maze using BFS.
As the algorithm searches for the shortest path to the goal ("X"), it considers neighboring cells and avoids obstacles.

The pathfinding process is visualized in real time:

Red "snake-like" trail: The explored path is shown in red ("X"), tracing the algorithm's steps.
Blue maze: The rest of the maze remains in blue.
When the goal is reached, the complete shortest path is highlighted in red.



