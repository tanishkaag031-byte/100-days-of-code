# Day 60: Logic Enhancers 🔤

## 📌 Overview
- **Day:** 60 / 100
- **Topic:** Logic Enhancers 🔤
- **Problems Covered:** Problem 110

---

## 📝 Problem 110

### Problem Statement
Write a program to take an integer array arr and an integer k as inputs. The task is to find the maximum element in each subarray of size k moving from left to right. Print the maximum elements for each window separated by spaces as output.

### Test Cases

#### Case 1
- **Input:** `arr[1, 2, 3, 1, 4, 5, 2, 3, 6] = , k = 3`
- **Output:** `3 3 4 5 5 5 6`
- **Explanation:** 1st contiguous subarray , max = 3; 2nd contiguous subarray , max = 3; 3rd contiguous subarray , max = 4; 4th contiguous subarray , max = 5; 5th contiguous subarray , max = 5; 6th contiguous subarray , max = 5; 7th contiguous subarray , max = 6.

#### Case 2
- **Input:** `arr[5, 1, 3, 4, 2] = , k = 1`
- **Output:** `5 1 3 4 2`
- **Explanation:** When k = 1, each element in the array is its own subarray, so the output is simply the same array.

---

## 💻 Solutions & Code
- [`logic10.c`](./logic10.c)

---

## 🧭 Navigation
- [⬅️ Previous: Day 59](../day_59/README.md)
- [➡️ Next: Day 61](../day_61/README.md)

