# Traveling-Salesman-Problem-TSP-Solution-using-Genetic-Algorithm

Introduction:
In the Traveling Salesman Problem (TSP), the objective is to find the shortest route for a salesman who needs to visit N cities, passing through each city exactly once, and returning to the starting city. This problem is considered NP-Hard and involves determining the optimal route among all possible city permutations. In this project, we aim to solve the TSP using a Genetic Algorithm and evaluate our approach using various datasets from the TSPLIB.

Part A: Exact Solution for TSP
Problem Statement:
Given a set of N cities, the goal is to compute the optimal tour length that visits each city exactly once and returns to the starting city. Solving this problem exactly involves exploring all possible city permutations which is not the optimal solution.

Approach:
We will implement an exact solution for the TSP using a brute-force approach. We will calculate the tour length for all possible permutations of cities and obtain the optimal tour length.

Execution:
Due to the time complexity of the brute-force approach, it is recommended to execute the code on a powerful machine or a cloud service like Google Colab (as I did). We will calculate the execution time for different datasets, including bayg29, d2103, and ali535, and report the results.

Part B: Genetic Algorithm Solution for TSP
Problem Statement:
The TSP is known to be NP-Hard, making it suitable for solving using metaheuristic algorithms like the Genetic Algorithm.

Approach:
We will use a Genetic Algorithm to solve the TSP. We will employ tournament selection, rotation-based crossover, and inversion mutation techniques. We will start with a random initial population and set parameters such as mutation rate and crossover rate.

Evaluation:
We will evaluate the Genetic Algorithm approach on various datasets, including bayg29, d2103, and ali535, sourced from TSPLIB. We will analyze the performance of the algorithm and compare the results with known optimal solutions.
