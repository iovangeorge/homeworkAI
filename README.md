# homeworkAI
AI homework computer science 

This repository contains implementations of three strategies to solve the Traveling Salesman Problem (TSP) in C++: Depth-First Search (DFS), Least-Cost (Uniform Cost) Search (UCS), and A* Search.

Overview

The Traveling Salesman Problem (TSP) is a classic optimization problem where the goal is to find the shortest route that visits a set of cities exactly once and returns to the starting city.

Implemented Strategies

Depth-First Search (DFS): An exhaustive strategy that explores all possible permutations of city sequences.
Least-Cost (Uniform Cost) Search (UCS): A strategy that explores paths in order of increasing cost, ensuring that the lowest-cost path is found first.
A Search*: A heuristic strategy that uses an informed search algorithm to guide exploration towards the most promising paths based on a heuristic function.

Compiling the Code
To compile the code, follow these steps:

1. Ensure you have a C++ compiler installed on your system. This code has been tested with GCC compiler version 9.3.0.

2. Clone the repository to your local machine.
        git clone <repository_url>

3. Navigate to the directory containing the source code files.
       cd TSP_Strategies_CPP
   
4. Compile the source code using the following command:
        g++ -o tsp_solver main.cpp dfs.cpp ucs.cpp astar.cpp -std=c++11
   Replace g++ with the appropriate command for your compiler if you're not using GCC.

5. Running the Application
  Once the code is compiled, you can run the application by executing the generated binary file. Use the following command:
            ./tsp_solver
   
Usage :
  The application provides a command-line interface. Upon running the executable, it will compute the minimum cost path for a predefined dataset using each strategy (DFS, UCS, and A* Search) and print the results to the console.
