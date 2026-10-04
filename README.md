# Day 52: Logic Enhancers 🔤

## 📌 Overview
- **Day:** 52 / 100
- **Topic:** Logic Enhancers 🔤
- **Problems Covered:** Problem 102

---

## 📝 Problem 102

### Problem Statement
Write a Program to take a sorted array arr[] and an integer x as input, find the index (0-based) of the smallest element in arr[] that is greater than or equal to x and print it. This element is called the ceil of x. If such an element does not exist, print -1. Note: In case of multiple occurrences of ceil of x, return the index of the first occurrence.

> 💡 **Note:** Follow-up(optional): Can you do it in O(log n) Time Complexity?

### Test Cases

#### Case 1
- **Input:** `arr = [1, 2, 8, 10, 11, 12, 19], x = 5`
- **Output:** `2`
- **Explanation:** Smallest number greater than 5 is 8, whose index is 2.

#### Case 2
- **Input:** `arr = [1, 2, 8, 10, 11, 12, 19], x = 20`
- **Output:** `-1`
- **Explanation:** No element greater than 20 is found. So output is -1.

#### Case 3
- **Input:** `arr = [1, 1, 2, 8, 10, 11, 12, 19], x = 0`
- **Output:** `0`
- **Explanation:** Smallest number greater than 0 is 1, whose indices are 0 and 1. The index of the first occurrence is 0.

#### Case 4
- **Input:** `arr = [1, 1, 2, 8, 10, 11, 12, 19], x = 2`
- **Output:** `2`
- **Explanation:** If x is directly present, return the index of its first occurrence.

---

## 💻 Solutions & Code
- [`q102_ceil_in_sorted_array.c`](./q102_ceil_in_sorted_array.c)

---

## 🧭 Navigation
- [⬅️ Previous: Day 51](../day_51/README.md)
- [➡️ Next: Day 53](../day_53/README.md)

