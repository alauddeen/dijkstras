# Graph Shortest Path Calculator

This repository contains a C++ application that calculates the shortest paths in a graph using Dijkstra's algorithm. It is capable of representing weighted graphs and determining the shortest path from a source node to all other nodes.

## File Structure

- `Graph.h`: Header file that declares the `Graph` class.
- `Main.cpp`: Main application file that includes Dijkstra's algorithm implementation and demonstration.

## Building the Project

To build this project, you need a C++ compiler that supports C++11 or later. The following instructions are for `g++`, which is commonly used on Unix-like systems.

1. Clone the repository to your local machine.
2. Navigate to the directory containing the cloned files.
3. Compile the project using the following command:

```bash
g++ -std=c++11 Main.cpp -o ShortestPathCalculator
```

## Running the Application

After compiling the code, you can run the application using the following command:

```bash
./ShortestPathCalculator
```

This will execute the `Main.cpp` program, which generates a graph with a predetermined number of vertices and edges, runs Dijkstra's algorithm from a specified source vertex, and prints the average shortest path length to each vertex.

## Features

- Efficient graph representation as an adjacency list.
- Priority queue implementation for optimized performance.
- Dijkstra's algorithm to compute shortest paths.
- Console output of the average shortest path length from the source node to every other node.
