# Traveling Salesman Problem (TSP)

*Introduction*
### What is the Traveling Salesman Problem?

The Traveling Salesman Problem (TSP) is a classic computational problem in the field of optimization. It involves finding the shortest possible route that visits a given set of cities exactly once and returns to the origin city. This problem has a wide range of applications in logistics, transportation, and other fields.

### Why is it challenging?

The TSP is classified as an NP-hard problem, meaning that finding an optimal solution becomes computationally intractable for large datasets. As the number of cities increases, the number of possible routes grows exponentially, making exhaustive search impractical.

### Our Approach
This project implements the Branch and Bound algorithm to tackle the TSP efficiently.
This algorithm explores the solution space intelligently by using a bounding function to prune unpromising branches, significantly reducing computational cost.

### Key features of our implementation:
Efficient Bounding: We employ a carefully designed bounding function to estimate the lower bound of a partial solution, helping to identify and discard suboptimal paths early in the search process.
Data Structures: Optimized data structures are used to represent the problem and solution space efficiently, improving performance.
Modular Design: The code is structured in a modular fashion, promoting code reusability and maintainability.

### Results and Evaluation
![image](https://github.com/user-attachments/assets/8e1e614d-1945-4334-8caa-4856ed8a6e10)
