# Deciphering Algorithmic Efficiency: From Divide & Conquer to TSP

## The Project
This repository explores how different algorithmic paradigms—Divide and Conquer, Greedy, and Dynamic Programming—handle real-world complexity. The goal was to move beyond theoretical Big O notation and observe how these strategies behave when faced with scaling datasets.

## Key Implementations
* **The Scaling Challenge**: A performance comparison between various sorting algorithms to identify where Divide and Conquer outshines simpler methods.
* **Resource Optimization**: Using Greedy and DP strategies to solve allocation problems.
* **The Wall of Complexity**: Implementing the Travelling Salesman Problem (TSP) to witness the transition from polynomial to exponential growth.

## Tech Stack & Profiling
* **Language**: Python 3.13
* **Profiling**: I utilized the built-in `tracemalloc` library for memory tracking and `time.perf_counter()` for high-precision timing.
* **Visualization**: `matplotlib` was used to transform raw performance logs into visual scalability trends.
