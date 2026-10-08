# Day 56: Logic Enhancers 🔤

## 📌 Overview
- **Day:** 56 / 100
- **Topic:** Logic Enhancers 🔤
- **Problems Covered:** Problem 106

---

## 📝 Problem 106

### Problem Statement
Write a program to take an array arr[] of integers as input, the task is to find the next greater element for each element of the array in order of their appearance in the array. Next greater element of an element in the array is the nearest element on the right which is greater than the current element. If there does not exist next greater of current element, then next greater element for current element is -1.

N.B:
- Print the output for each element in a comma separated fashion.
- Do not use Stack, use brute force approach (nested loop) to solve.

> 💡 **Note:** Try solving this using brute force (nested loop). No need of attempting the optimized stack-based solution.

### Test Cases

#### Case 1
- **Input:** `arr = [1, 3, 2, 4]`
- **Output:** `3, 4, 4, -1`
- **Explanation:** The next larger element to 1 is 3, for 3 it is 4, for 2 it is 4 and for 4 there is no next greater element so it is -1.

#### Case 2
- **Input:** `arr = [6, 8, 0, 1, 3]`
- **Output:** `8, -1, 1, 3, -1`
- **Explanation:** Next greater element for 6 is 8, for 8 it is -1, for 0 it is 1, for 1 it is 3 and for 3 there is no greater element on right hence -1.

#### Case 3
- **Input:** `arr = [1, 2, 3, 5]`
- **Output:** `2, 3, 5, -1`
- **Explanation:** In a sorted array, each element’s next greater is its immediate next element except for the last element which has none, so -1.

#### Case 4
- **Input:** `arr = [5, 4, 3, 1]`
- **Output:** `-1, -1, -1, -1`
- **Explanation:** No element has a greater element on its right, so all next greater elements are -1.

---

## 💻 Solutions & Code
- [`logic6.c`](./logic6.c)

---

## 🧭 Navigation
- [⬅️ Previous: Day 55](../day_55/README.md)
- [➡️ Next: Day 57](../day_57/README.md)

