# Catch the Thief: A Graph Theory Approach

This repository provides solutions to the "Catch the Thief" puzzle using two different approaches: **NetworkX** and a **from-scratch** implementation. The problem is modeled as a directed graph, where nodes represent locations in a city or a prison, and edges represent the connections between them. The objective is to create an efficient strategy for the police to catch a thief who is attempting to evade capture by moving between adjacent nodes.

### Project Breakdown:

1. **City Layout (Part 1)**:
    - In this scenario, the goal is to determine possible locations where the thief can be caught based on the structure of the graph, the police’s movement (to adjacent nodes), and the thief’s movement (trying to evade).
    - **NetworkX Approach**: Utilizes the powerful NetworkX library to model the graph, representing locations and connections, and applies graph traversal algorithms to identify where the police can catch the thief.
    - **From-Scratch Approach**: Implements graph traversal algorithms (such as BFS and DFS) from scratch to model police and thief movements and to find the optimal locations for the thief’s capture.

2. **Prison Escape (Part 2)**:
    - After the thief is captured and placed in prison, the challenge shifts to finding the thief within the prison using graph traversal.
    - **NetworkX Approach**: Uses NetworkX to create the prison graph and execute BFS/DFS to simulate the search for the thief.
    - **From-Scratch Approach**: Implements the same BFS/DFS algorithms manually to track both the police and the thief’s movements through the prison's graph.

### Key Features:
- **Graph Models**: City and prison layouts are represented as directed graphs using both NetworkX and a custom from-scratch solution.
- **Graph Traversal Algorithms**: Depth-First Search (DFS) and Breadth-First Search (BFS) are applied to simulate the movements of the police and thief.
- **Python Simulations**: The repository includes Python code to simulate the police's and thief's movements and visualize the process of capturing the thief.
