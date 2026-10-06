# Day 54: Logic Enhancers 🔤

## 📌 Overview
- **Day:** 54 / 100
- **Topic:** Logic Enhancers 🔤
- **Problems Covered:** Problem 104

---

## 📝 Problem 104

### Problem Statement
Write a Program to take a positive integer n as input, and find the pivot integer x such that the sum of all elements between 1 and x inclusively equals the sum of all elements between x and n inclusively. Print the pivot integer x. If no such integer exists, print -1. Assume that it is guaranteed that there will be at most one pivot integer for the given input.

> 💡 **Note:** Follow-up 1 (optional): Can you do it in O(log n) Time Complexity? Follow-up 2 (optional): Can you do it in O(1) Time Complexity?

### Test Cases

#### Case 1
- **Input:** `n = 8`
- **Output:** `6`
- **Explanation:** 6 is the pivot integer since: 1 + 2 + 3 + 4 + 5 + 6 = 6 + 7 + 8 = 21.

#### Case 2
- **Input:** `n = 1`
- **Output:** `1`
- **Explanation:** 1 is the pivot integer since: 1 = 1.

#### Case 3
- **Input:** `n = 4`
- **Output:** `-1`
- **Explanation:** It can be proved that no such integer exists.

---

## 💻 Solutions & Code
- [`logic4.c`](./logic4.c)

---

## 🧭 Navigation
- [⬅️ Previous: Day 53](../day_53/README.md)
- [➡️ Next: Day 55](../day_55/README.md)

