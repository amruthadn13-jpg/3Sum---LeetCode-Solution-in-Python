# 3Sum - LeetCode Solution in Python

## Overview

This project contains a Python solution for the LeetCode problem **3Sum**.

The program finds all unique triplets in an array whose sum equals zero.

---

## Problem Statement

Given an integer array `nums`, return all unique triplets:

```text
[nums[i], nums[j], nums[k]]
```

such that:

```text
nums[i] + nums[j] + nums[k] == 0
```

The solution set must not contain duplicate triplets.

---

## Approach Used

This solution uses:

* Sorting
* Two-pointer technique

### Steps:

1. Sort the array
2. Traverse the array using a loop
3. Fix one element
4. Use two pointers:

   * Left pointer
   * Right pointer
5. Move pointers based on the sum value
6. Skip duplicate elements to avoid repeated triplets

---

## Algorithm Type

* Sorting
* Two Pointer Technique

---

## Time Complexity

```text
O(n²)
```

The array is traversed using nested pointer movement.

---

## Space Complexity

```text
O(1)
```

Ignoring the output array.

---

## Key Python Concepts Used

* List sorting
* While loops
* Two-pointer approach
* Conditional statements
* Duplicate handling

---

## Example

### Input

```text
nums = [-1, 0, 1, 2, -1, -4]
```

### Output

```text
[[-1, -1, 2], [-1, 0, 1]]
```

### Explanation

```text
The triplets add up to zero and duplicate combinations are avoided.
```

---

## Learning Outcomes

* Understanding the two-pointer technique
* Optimizing brute-force solutions
* Handling duplicates efficiently
* Improving array problem-solving skills

---

## Real-World Importance

The two-pointer technique is widely used in:

* Array optimization problems
* Interview coding questions
* Search-based algorithms
* Data processing tasks

---

## Author

Amrutha D N

