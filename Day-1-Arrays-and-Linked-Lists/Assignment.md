# Assignment: Arrays and Linked Lists

## Arrays

### Question 1: **Max Consecutive Sum**

Write a function in JavaScript that takes an array of integers and returns the maximum sum of consecutive elements in the array. For example, given the array `[1, -2, 3, 4, -1, 5]`, the function should return `11`, which is the sum of `[3, 4, -1, 5]`.

**Sample Code:**

```javascript
function maxConsecutiveSum(arr) {
  // Your code here
}
```

### Question 2: **Rotate Array**

Write a function that rotates an array to the right by a given number of steps. For instance, given the array `[1, 2, 3, 4, 5]` and `2` steps, the array should become `[4, 5, 1, 2, 3]`.

**Sample Code:**

```javascript
function rotateArray(arr, steps) {
  // Your code here
}
```

## Linked Lists

### Question 1: **Reverse Linked List**

Implement a function to reverse a singly linked list in JavaScript. You may use the `Node` and `LinkedList` classes you've learned about. Ensure your function directly modifies the linked list.

**Sample Code:**

```javascript
class Node {
  constructor(data) {
    this.data = data;
    this.next = null;
  }
}

class LinkedList {
  constructor() {
    this.head = null;
  }

  add(data) {
    let newNode = new Node(data);
    if (!this.head) {
      this.head = newNode;
    } else {
      let current = this.head;
      while (current.next) {
        current = current.next;
      }
      current.next = newNode;
    }
  }

  reverse() {
    // Your code here
  }

  printList() {
    let current = this.head;
    while (current) {
      console.log(current.data);
      current = current.next;
    }
  }
}
```

### Question 2: **Find Middle Element**

Write a function that finds and returns the middle element of a singly linked list. If the list has an even number of elements, return the second of the two middle elements. Assume that you cannot use any extra space (no storing elements in an array, for example), and that you should find the middle element in a single pass through the linked list.

**Sample Code:**

```javascript
class Node {
  constructor(data) {
    this.data = data;
    this.next = null;
  }
}

class LinkedList {
  constructor() {
    this.head = null;
  }

  add(data) {
    let newNode = new Node(data);
    if (!this.head) {
      this.head = newNode;
    } else {
      let current = this.head;
      while (current.next) {
        current = current.next;
      }
      current.next = newNode;
    }
  }

  findMiddle() {
    // Your code here
  }

  printList() {
    let current = this.head;
    while (current) {
      console.log(current.data);
      current = current.next;
    }
  }
}
```

## Submission Guidelines

- Write your solutions in a separate JavaScript file for each problem.
- Make sure your code runs correctly and handles different test cases.
- Submit your files through the course platform before the deadline.
