# Assignment: Wrap-Up and Advanced Topics Overview

## Recap of Key Concepts

### Question 1: **Concept Review Quiz**

Create a quiz consisting of multiple-choice and true/false questions covering key concepts from the course. Topics may include data structures, algorithms, problem-solving techniques, and their applications.

**Sample Questions:**

1. What is the time complexity of inserting an element into an AVL tree?
   - A) O(1)
   - B) O(log n)
   - C) O(n)
   - D) O(n log n)

2. True or False: QuickSort is a stable sorting algorithm.

3. Which data structure is best suited for implementing LRU (Least Recently Used) cache?
   - A) Stack
   - B) Queue
   - C) Linked List
   - D) Hash Table

## Introduction to Advanced Topics

### Question 2: **Sorting Algorithms Comparison**

Write JavaScript functions to implement and compare the performance of different sorting algorithms (e.g., QuickSort, MergeSort, HeapSort). Use arrays of various sizes as input and measure the time taken for sorting.

**Sample Code:**

```javascript
function quickSort(arr) {
  // Your code here
}

function mergeSort(arr) {
  // Your code here
}

// Other sorting functions...

// Measure performance
const arrayToSort = [...]; // Initialize array with data
console.time("QuickSort");
quickSort(arrayToSort);
console.timeEnd("QuickSort");
```

### Question 3: **Hash Table Implementation**

Implement a basic hash table in JavaScript. Include functions for inserting key-value pairs, retrieving values by key, and handling collisions using chaining or open addressing.

**Sample Code:**

```javascript
class HashTable {
  constructor(size) {
    // Your code here
  }

  insert(key, value) {
    // Your code here
  }

  get(key) {
    // Your code here
  }
}

// Test the hash table
const table = new HashTable(10);
table.insert("key1", "value1");
console.log(table.get("key1")); // Output: value1
```

## Submission Guidelines

- Write your solutions in separate JavaScript files for each problem.
- Ensure your code runs correctly and handles different test cases.
- Include comments to explain your approach and any assumptions made.
- Submit your files through the course platform before the deadline.

---
