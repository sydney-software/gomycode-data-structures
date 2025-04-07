 Algorithm Solutions in JavaScript

Welcome to the **Algorithm Solutions** repository! This project provides implementations for solving two distinct algorithmic problems using JavaScript. The goal is to offer simple, efficient, and understandable solutions to common programming challenges.

---

 Problem 1: Sum of Distinct Elements

 Description
Given two arrays (representing sets), the task is to calculate the sum of all distinct elements that are present in either of the sets.

 Example
Input:
- Set 1: `[3, 1, 7, 9]`
- Set 2: `[2, 4, 1, 9, 3]`

Output:
- `13` (Distinct elements: `4, 7, 2`)

 Implementation
- Combines elements from both sets into one array.
- Uses a dictionary to track the occurrences of each element.
- Calculates the sum of elements that appear only once.



 Problem 2: Dot Product and Orthogonal Check

 Description
This problem involves vector operations:
1. Calculate the **dot product** (scalar product) of two vectors.
2. Determine whether two vectors are orthogonal (the dot product of orthogonal vectors is zero).

 Example
- Input Vectors:
  1. `v1 = [1, 0]`, `v2 = [0, 1]` --> Orthogonal
  2. `v1 = [1, 2, 3]`, `v2 = [4, 5, 6]` --> Not Orthogonal

  Output:
  - Vectors `[1, 0]` and `[0, 1]` are orthogonal.
  - Vectors `[1, 2, 3]` and `[4, 5, 6]` are NOT orthogonal.

 Implementation
- Uses a function `dotProduct` to compute the scalar product.
- Checks pairs of vectors for orthogonality by verifying if the dot product equals zero.



 Getting Started

 Prerequisites
Ensure that you have:
- A working installation of Node.js or JavaScript runtime to execute the code.

