# Day 76: File Handling 📁

## 📌 Overview
- **Day:** 76 / 100
- **Topic:** File Handling 📁
- **Problems Covered:** Problem 126

---

## 📝 Problem 126

### Problem Statement
Ask the user for a filename. Check if it exists by trying to open it in read mode. If the file pointer is NULL, print an error message; otherwise, read and display its content.

### Test Cases

#### Case 1
- **Input:** `Filename: sample.txt (File Exists: Yes)`
- **Output:**
  ```text
File opened successfully.
(Displays file content)
  ```
- **Explanation:** The program opens the existing file and prints its content using fgets().

#### Case 2
- **Input:** `Filename: nofile.txt (File Exists: No)`
- **Output:** `Error: File does not exist!`
- **Explanation:** Since fopen() returns NULL, an error message is displayed instead of reading.

---

## 💻 Solutions & Code
- [`file7.c`](./file7.c)

---

## 🧭 Navigation
- [⬅️ Previous: Day 75](../day_75/README.md)
- [➡️ Next: Day 77](../day_77/README.md)

