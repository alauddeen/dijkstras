# Graph Shortest Path Calculator

## Introduction

This C++ project implements Dijkstra's algorithm, which is a classic algorithm in computer science for finding the shortest paths between nodes in a graph. The graph is assumed to have weighted edges with non-negative weights.

## Implementation Details

- `Graph`: A class that represents a graph structure using an adjacency list. It allows for efficient access to the graph's vertices and edges and provides methods for adding edges and retrieving neighboring vertices.

- `PriorityQueue`: A custom priority queue class that aids Dijkstra's algorithm. It is implemented using a binary heap to efficiently manage and retrieve the next vertex with the shortest tentative distance during the algorithm's execution.

- `ShortestPath`: This class uses the `Graph` and `PriorityQueue` classes to compute the shortest paths from a single source vertex to all other vertices in the graph. It encapsulates the logic for Dijkstra's algorithm.

## Core Functionality

- The code calculates the shortest path from a source node to every other node in the graph.
- It demonstrates the use of object-oriented principles in C++ to encapsulate the components of Dijkstra's algorithm, such as graph representation and priority queue management.
- It includes a main function that sets up a sample graph with vertices and weighted edges, and then it executes the shortest path calculation.

## Project Structure

The project is divided into two main files:
- **Graph.h**: Contains the declaration of the `Graph` class.
- **Main.cpp**: Includes the `main` function where the `Graph` and `ShortestPath` classes are utilized to demonstrate the algorithm.

## Objective

The primary goal of this project is to provide a clear and concise implementation of Dijkstra's algorithm, showcasing how it can be applied to compute shortest paths in weighted graphs. This serves as an educational resource for understanding and analyzing the efficiency of Dijkstra's algorithm in pathfinding problems in graphs.

