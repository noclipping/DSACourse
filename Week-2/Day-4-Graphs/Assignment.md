# Assignment: Graphs and Basic Graph Algorithms

## Graph Representation

### Question 1: **Adjacency Matrix**

Write a function in JavaScript to create an adjacency matrix for a given undirected graph. The function should take the number of vertices and an array of edges as input and return the adjacency matrix.

**Sample Input/Output:**

- Input: `4`, `[[0, 1], [1, 2], [2, 3], [3, 0]]`
  Output:

  ```
  [
    [0, 1, 0, 1],
    [1, 0, 1, 0],
    [0, 1, 0, 1],
    [1, 0, 1, 0]
  ]
  ```

**Sample Code:**

```javascript
function createAdjacencyMatrix(numVertices, edges) {
  // Your code here
}
```

## Graph Traversal

### Question 2: **Depth-First Search (DFS)**

Implement the Depth-First Search algorithm in JavaScript to traverse a graph starting from a given vertex. You may assume that the graph is represented as an adjacency list.

**Sample Code:**

```javascript
function dfs(graph, startVertex) {
  // Your code here
}
```

## Pathfinding Algorithms

### Question 3: **Dijkstra's Shortest Path Algorithm**

Write a function in JavaScript to find the shortest path from a given source vertex to all other vertices in a weighted graph using Dijkstra's algorithm. You may assume that the graph is represented as an adjacency list and that all edge weights are non-negative.

**Sample Code:**

```javascript
function dijkstra(graph, sourceVertex) {
  // Your code here
}
```

## Submission Guidelines

- Write your solutions in separate JavaScript files for each problem.
- Ensure your code runs correctly and handles different test cases.
- Submit your files through the course platform before the deadline.

---
