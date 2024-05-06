# Assignment: Trees and Binary Search Trees

## Trees

### Question 1: **Binary Tree Traversal**

Implement functions in JavaScript to perform in-order, pre-order, and post-order traversals of a binary tree. You may assume that each node in the tree has a structure with a `value`, `left`, and `right` property.

**Sample Code:**

```javascript
class TreeNode {
  constructor(value) {
    this.value = value;
    this.left = null;
    this.right = null;
  }
}

function inOrderTraversal(root) {
  // Your code here
}

function preOrderTraversal(root) {
  // Your code here
}

function postOrderTraversal(root) {
  // Your code here
}
```

### Question 2: **Binary Tree Height**

Write a function in JavaScript to find the height of a binary tree. The height of a binary tree is the length of the longest path from the root node to a leaf node.

**Sample Code:**

```javascript
function treeHeight(root) {
  // Your code here
}
```

## Binary Search Trees (BSTs)

### Question 1: **BST Validation**

Write a function in JavaScript to determine if a given binary tree is a valid binary search tree (BST). A BST is valid if for each node, its value is greater than all values in its left subtree and less than all values in its right subtree.

**Sample Code:**

```javascript
function isValidBST(root) {
  // Your code here
}
```

### Question 2: **BST Successor**

Given a node in a binary search tree, write a function to find its in-order successor. The in-order successor of a node is the node with the smallest key greater than the node's key.

**Sample Code:**

```javascript
class TreeNode {
  constructor(value) {
    this.value = value;
    this.left = null;
    this.right = null;
    this.parent = null; // Optional: Parent pointer
  }
}

function inOrderSuccessor(root, node) {
  // Your code here
}
```

## Submission Guidelines

- Write your solutions in separate JavaScript files for each problem.
- Ensure your code runs correctly and handles different test cases.
- Submit your files through the course platform before the deadline.

---

This assignment challenges you to apply your understanding of trees and binary search trees to solve practical problems. Let me know if you need any further assistance or modifications!