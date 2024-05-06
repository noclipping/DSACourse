# FAQ: Dynamic Programming and Greedy Algorithms

## Dynamic Programming

### What is dynamic programming?

Dynamic programming is a method for solving complex problems by breaking them down into simpler subproblems. It involves solving each subproblem only once and storing the solution to avoid redundant computations.

### What are the key components of dynamic programming?

- **Optimal Substructure**: The optimal solution of the problem can be constructed from optimal solutions of its subproblems.
- **Overlapping Subproblems**: Subproblems may recur many times, and solutions to them can be cached and reused.

### When should I use dynamic programming?

Dynamic programming is useful for solving optimization problems where the solution depends on the solutions to smaller subproblems. It is particularly effective when the problem has overlapping subproblems and exhibits optimal substructure.

## Greedy Algorithms

### What is a greedy algorithm?

A greedy algorithm makes a series of choices at each step, aiming to find the optimal solution for the whole problem. It makes the locally optimal choice at each step with the hope of finding a global optimum.

### How does a greedy algorithm differ from dynamic programming?

- **Optimality**: Greedy algorithms may not always produce optimal solutions, while dynamic programming guarantees optimal solutions.
- **Efficiency**: Greedy algorithms are often more efficient but may not always produce the best result.

### When should I use a greedy algorithm?

Greedy algorithms are suitable for solving optimization problems where making the locally optimal choice at each step leads to a globally optimal solution. They are often used when finding the globally optimal solution is not necessary or too computationally expensive.

## General

### How can I practice dynamic programming and greedy algorithms?

You can practice dynamic programming and greedy algorithms by solving a variety of problems on online coding platforms such as LeetCode, HackerRank, and Codeforces. Start with simpler problems and gradually move on to more complex ones.

### What are some common mistakes to avoid when working with dynamic programming and greedy algorithms?

- **Not identifying optimal substructure**: Ensure that the problem can be broken down into smaller subproblems with an optimal solution.
- **Forgetting to handle base cases**: Always consider the base cases when solving recursive problems with dynamic programming.
- **Assuming greedy choice always leads to optimal solution**: Verify that the greedy choice at each step indeed leads to the optimal solution for the entire problem.

---
