# Day 61: Logic Enhancers 🔤

## 📌 Overview
- **Day:** 61 / 100
- **Topic:** Logic Enhancers 🔤
- **Problems Covered:** Problem 111

---

## 📝 Problem 111

### Problem Statement
Write a program to take an integer array arr and an integer k as inputs. The task is to find the first negative integer in each subarray of size k moving from left to right. If no negative exists in a window, print "0" for that window. Print the results separated by spaces as output.

### Test Cases

#### Case 1
- **Input:** `arr[] = [-8, 2, 3, -6, 10], k = 2`
- **Output:** `-8 0 -6 -6`
- **Explanation:** Window [-8, 2] First negative integer is -8. Window No negative integers, output is 0. Window [3, -6] First negative integer is -6. Window [-6, 10] First negative integer is -6.

#### Case 2
- **Input:** `arr[] = [12, -1, -7, 8, -15, 30, 16, 28], k = 3`
- **Output:** `-1 -1 -7 -15 -15 0`
- **Explanation:** Window [12, -1, -7] First negative integer is -1. Window [-1, -7, 8] First negative integer is -1. Window [-7, 8, -15] First negative integer is -7. Window [8, -15, 30] First negative integer is -15. Window [-15, 30, 16] First negative integer is -15. Window No negative integers, output is 0.

#### Case 3
- **Input:** `arr[] = [12, 1, 3, 5], k = 3`
- **Output:** `0 0`
- **Explanation:** Window No negative integers, output is 0. Window No negative integers, output is 0.

---

## 💻 Solutions & Code
- [`logic11.c`](./logic11.c)

---

## 🧭 Navigation
- [⬅️ Previous: Day 60](../day_60/README.md)
- [➡️ Next: Day 62](../day_62/README.md)

