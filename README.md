# Map Navigator
# Grid-based navigation using A* algorithm with Manhattan distance heuristic.
# Description
This project demonstrates a grid-based navigation system using the A* algorithm with the Manhattan distance heuristic. The purpose is to simulate pathfinding in a grid environment, allowing a player to navigate from a start position to a goal position while avoiding obstacles.

# Features
Grid Representation: A 10x10 grid where each cell can be empty, contain an obstacle ('X'), or mark the player's position ('P') and the goal ('G').
Player Movement: Move the player using the WASD keys to navigate the grid.
Pathfinding Algorithm: Implements the A* algorithm to find the shortest path to the goal, considering obstacles.
Heuristic Function: Utilizes the Manhattan distance to estimate the shortest path.
Distance Calculation: Displays the remaining distance to the goal from the player's current position.
# How It Works
Map Setup: The grid is initialized with obstacles, a player starting position, and a goal.
A Algorithm:* The A* algorithm calculates the shortest path from the player's position to the goal, considering obstacles.
Player Navigation: The player can move in four directions (up, down, left, right) to navigate the grid.
Goal Detection: The program checks if the player has reached the goal and congratulates the player upon success.
# Usage
Compile the Code: Ensure you have a C++ compiler installed. Compile the code using a command like g++ -std=c++11 main.cpp -o navigator.
Run the Program: Execute the compiled program using ./navigator.
Control the Player: Use the WASD keys to move the player. Try to reach the goal while avoiding obstacles.
# Example Output
# Copy code
# . . . . . G . . . .
# . X . X . . X . X .
# . X P X . . X . X .
# . . . . . . . . . .
# . X . X . . X . X .
# . . . . . . . . . .
# . X . X . . X . X .
# . . . . . . . . . .
# . X . X . . X . X .
# . . . . . . . . . .
# Distance to goal: 5
# Enter a move (WASD to move, Q to quit): 
