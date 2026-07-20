<h1 align="center">🚀 NumPy for AI & Machine Learning</h1>

<p align="center">
A beginner-friendly repository covering the essential NumPy concepts required for
<b>Artificial Intelligence, Machine Learning, and Data Science.</b>
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![NumPy](https://img.shields.io/badge/NumPy-Learning-orange?style=for-the-badge&logo=numpy)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![AI](https://img.shields.io/badge/AI-Ready-brightgreen?style=for-the-badge)

</p>

---

# 📖 About

This repository contains my complete **NumPy learning journey** with structured Jupyter notebooks, practical examples, interview-focused concepts, and coding exercises.

---

# 📚 Topics Covered

| ✔ | Topic |
|:-:|----------------------------|
| ✅ | Arrays |
| ✅ | Array Indexing & Slicing |
| ✅ | Boolean Indexing |
| ✅ | Array Operations |
| ✅ | Broadcasting |
| ✅ | Matrix Operations |
| ✅ | Aggregation Functions |
| ✅ | Axis |
| ✅ | Universal Functions |
| ✅ | Stacking & Splitting |
| ✅ | Sorting & Searching |
| ✅ | Linear Algebra |
| ✅ | Practice Questions |

---

# 📂 Repository Structure

```text
📦 NumPy
│
├── 📓 Arrays.ipynb
├── 📓 Array_Indexing.ipynb
├── 📓 Array_Operations.ipynb
├── 📓 Practice.ipynb
├── 📓 Exercises.ipynb
├── 📄 README.md
└── 🚫 .gitignore
```

---

# 📊 NumPy at a Glance

```text
                 NumPy
                   │
      ┌────────────┼────────────┐
      │            │            │
   Arrays      Operations    Linear Algebra
      │            │            │
 Indexing     Broadcasting   Matrix Math
      │            │            │
 Slicing      Aggregation    AI & ML
```

---

# 🔢 Array Example

```python
import numpy as np

arr = np.array([10, 20, 30, 40, 50])
```

```text
Index →   0    1    2    3    4

Array →  10   20   30   40   50
```

---

# ✂️ Array Slicing

```python
arr[1:4]
```

```text
Array → 10   20   30   40   50
               ├──────────┤

Result →      20   30   40
```

---

# 🎯 Boolean Indexing

```python
arr[arr > 30]
```

```text
Array      10   20   30   40   50

Condition   ❌   ❌   ❌   ✅   ✅

Output →          40   50
```

---

# ⚡ Broadcasting

```python
A = [[1],
     [2],
     [3]]

B = [10,20,30]
```

```text
      [1]          [10 20 30]

      [2]     +    

      [3]

              ↓

 11   21   31

 12   22   32

 13   23   33
```

---

# 🧮 Matrix Multiplication

```text
Matrix A              Matrix B

┌───────┐            ┌───────┐
│ 1  2  │            │ 5  6  │
│ 3  4  │     ×      │ 7  8  │
└───────┘            └───────┘

            ↓

┌────────────┐
│ 19    22   │
│ 43    50   │
└────────────┘
```

---

# 🔄 Reshape

```python
arr.reshape(2,3)
```

```text
1 2 3 4 5 6

↓

┌─────────┐
│ 1 2 3   │
│ 4 5 6   │
└─────────┘
```

---

---

# 🛠 Tech Stack

- 🐍 Python
- 📊 NumPy
- 📓 Jupyter Notebook

---

# ⭐ Support

If you found this repository helpful,

⭐ Star the repository

🍴 Fork the repository

📢 Share it with others

---

<p align="center">
<b>⭐ Happy Learning! ⭐</b>
</p>