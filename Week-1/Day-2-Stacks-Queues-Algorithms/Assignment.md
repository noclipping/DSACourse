# Assignment: Stacks, Queues, and Algorithmic Thinking

## Stacks and Queues

### Question 1: **Valid Parentheses**

Write a function in JavaScript that takes a string containing just the characters '(', ')', '{', '}', '[' and ']', and determines if the input string is valid. The function should return true if the string is valid, and false otherwise.

**Sample Input/Output:**

- Input: `"()[]{}"`
  Output: `true`

- Input: `"([)]"`
  Output: `false`

**Sample Code:**

```javascript
function isValidParentheses(s) {
  // Your code here
}
```

### Question 2: **Queue Reconstruction by Height**

Suppose you have a random list of people standing in a queue. Each person is described by a pair of integers `(h, k)`, where `h` is the height of the person and `k` is the number of people in front of this person who have a height greater than or equal to `h`. Write a function to reconstruct the queue.

**Sample Input/Output:**

- Input: `[[7,0],[4,4],[7,1],[5,0],[6,1],[5,2]]`
  Output: `[[5,0],[7,0],[5,2],[6,1],[4,4],[7,1]]`

**Sample Code:**

```javascript
function reconstructQueue(people) {
  // Your code here
}
```

## Algorithmic Thinking

### Question 1: **Binary Search Implementation**

Implement the binary search algorithm in JavaScript. Your function should take a sorted array and a target value as input and return the index of the target value if it exists in the array, otherwise return -1.

**Sample Code:**

```javascript
function binarySearch(arr, target) {
  // Your code here
}
```

### Question 2: **Greedy Algorithm: Activity Selection Problem**

Given a set of activities with start and finish times, the task is to select the maximum number of activities that can be performed by a single person, assuming that a person can only work on a single activity at a time. Implement the greedy algorithm to solve this problem.

**Sample Input:**

```
Activities: [(1, 3), (2, 5), (0, 4), (4, 6), (5, 7), (7, 9), (8, 10), (9, 11)]
```

**Sample Output:**

```
Selected Activities: [(1, 3), (4, 6), (7, 9), (9, 11)]
```

**Sample Code:**

```javascript
function maxActivities(activities) {
  // Your code here
}
```

## Submission Guidelines

- Write your solutions in separate JavaScript files for each problem.
- Ensure your code runs correctly and handles different test cases.
- Submit your files through the course platform before the deadline.

---