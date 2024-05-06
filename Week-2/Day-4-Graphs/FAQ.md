# FAQ: Graphs and Basic Graph Algorithms

## Graph Representation

### What is an adjacency matrix?

An adjacency matrix is a 2D array used to represent connections between vertices in a graph. Each cell in the matrix indicates whether there is an edge between the corresponding vertices.

### What is an adjacency list?

An adjacency list is a collection of lists or arrays, where each vertex maintains a list of adjacent vertices. It is a more space-efficient way to represent sparse graphs compared to an adjacency matrix.

### When should I use an adjacency matrix versus an adjacency list?

- **Adjacency Matrix**: Ideal for dense graphs (where most pairs of vertices are connected) or when edge presence needs to be checked quickly.
- **Adjacency List**: Suitable for sparse graphs (where few pairs of vertices are connected) or when memory usage is a concern.

## Graph Traversal

### What is Depth-First Search (DFS)?

Depth-First Search (DFS) is a graph traversal algorithm that explores as far as possible along each branch before backtracking. It is often used to traverse or search tree or graph structures.

### What is Breadth-First Search (BFS)?

Breadth-First Search (BFS) is a graph traversal algorithm that explores all neighbor vertices at the present depth level before moving to the next depth level. It is typically used to find the shortest path in unweighted graphs.

### When should I use DFS versus BFS?

- **DFS**: Useful for topological sorting, cycle detection, and solving maze-like problems.
- **BFS**: Ideal for finding the shortest path in unweighted graphs, level-order traversal, and solving puzzles with multiple solutions.

## Pathfinding Algorithms

### What is Dijkstra's algorithm?

Dijkstra's algorithm is a shortest path algorithm used to find the shortest path from a single source vertex to all other vertices in a weighted graph with non-negative edge weights. It guarantees the shortest path if all edge weights are non-negative.

### What is A* algorithm?

A* (A-star) algorithm is a heuristic-based search algorithm used for finding the shortest path between two nodes in a graph. It combines the benefits of both uniform cost search and greedy search by using heuristics to guide the search process.

### How do I choose between Dijkstra's algorithm and A* algorithm?

- **Dijkstra's Algorithm**: Suitable for finding the shortest path in graphs with non-negative edge weights.
- **A* Algorithm**: Ideal for finding the shortest path in graphs with non-negative edge weights and a good heuristic function, especially in grid-based pathfinding problems.

---
