# Deciphering Algorithmic Efficiency: From Divide & Conquer to TSP

## The Project
This repository explores how different algorithmic paradigms—Divide and Conquer, Greedy, and Dynamic Programming—handle real-world complexity. [cite_start]The goal was to move beyond theoretical Big O notation and observe how these strategies behave when faced with scaling datasets[cite: 3, 10].

## Key Implementations
* [cite_start]**The Scaling Challenge**: A performance comparison between various sorting algorithms to identify where Divide and Conquer outshines simpler methods[cite: 6, 29].
* [cite_start]**Resource Optimization**: Using Greedy and DP strategies to solve allocation problems[cite: 7, 8].
* [cite_start]**The Wall of Complexity**: Implementing the Travelling Salesman Problem (TSP) to witness the transition from polynomial to exponential growth[cite: 9, 29].

## Tech Stack & Profiling
* **Language**: Python 3.13
* [cite_start]**Profiling**: I utilized the built-in `tracemalloc` library for memory tracking and `time.perf_counter()` for high-precision timing[cite: 44, 45].
* [cite_start]**Visualization**: `matplotlib` was used to transform raw performance logs into visual scalability trends[cite: 26, 45].
