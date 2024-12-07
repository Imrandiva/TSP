# Traveling Salesman Problem Solver

This project implements a heuristic solution to the **Traveling Salesman Problem (TSP)**, a classic optimization challenge. The goal of TSP is to find the shortest possible route that visits each city exactly once and returns to the starting point.

## Features

- **Input**: Takes a list of cities with their 2D coordinates.
- **Distance Calculation**: Computes pairwise Euclidean distances between cities.
- **Greedy Algorithm**: Generates an initial tour based on a greedy heuristic.
- **Lin-Kernighan Heuristic**: Refines the tour to reduce the overall distance.
- **Edge Manipulation**: Includes edge-based operations to reconstruct tours and optimize paths further.

## How It Works

1. **Input**: The program reads the number of cities and their coordinates.
2. **Distance Matrix**: A symmetric matrix is created to store distances between every pair of cities.
3. **Initial Tour**: A greedy algorithm finds an initial feasible route.
4. **Optimization**: The Lin-Kernighan heuristic is applied to iteratively improve the solution.
5. **Output**: The final optimized tour is printed.

## Usage

### Compile and Run

1. Compile the program using a C++ compiler:
   
   ```bash
   g++ main.cpp -o tsp_solver
    ```