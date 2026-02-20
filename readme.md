# 🧠 LeetCode Solutions

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white)

A collection of **300+ LeetCode problem solutions**, organized by category and challenge type.

---

## 📂 Repository Structure

```
leetcode/
├── 📁 top_interview_questions/
│   ├── 1_easy/                     # 95 problems
│   │   ├── 1_array/
│   │   ├── 2_strings/
│   │   ├── 3_linked_list/
│   │   ├── 4_trees/
│   │   ├── 5_sorting_and_searching/
│   │   ├── 6_dynamic_programming/
│   │   ├── 7_design/
│   │   ├── 8_math/
│   │   └── 9_others/
│   └── 2_medium/                   # 60 problems
│       ├── 1_array_and_strings/
│       ├── 2_linked_list/
│       ├── 3_trees_and_graphs/
│       ├── 4_backtracking/
│       ├── 5_sorting_and_searching/
│       ├── 6_dynamic_programming/
│       ├── 7_design/
│       ├── 8_math/
│       └── 9_others/
├── 📁 algorithms/                  # 61 general algorithm problems
├── 📁 30_day_challenge/            # April 2020  — 27 problems
├── 📁 may_challenge/               # May 2020    — 31 problems
├── 📁 june_challenge/              # June 2020   — 21 problems
├── 📁 august_challenge/            # Aug 2020    —  5 problems
└── 📁 database/                    # 8 SQL problems
```

---

## 📊 Statistics

| Category | Problems | Language |
|---|---|---|
| Top Interview Questions (Easy) | 95 | Python |
| Top Interview Questions (Medium) | 60 | Python |
| Algorithms | 61 | Python, Go |
| 30-Day Challenge | 27 | Python |
| May Challenge | 31 | Python |
| June Challenge | 21 | Python |
| August Challenge | 5 | Python |
| Database | 8 | SQL |
| **Total** | **308** | |

---

## 🏷️ Topics Covered

- **Data Structures** — Arrays, Strings, Linked Lists, Trees, Graphs, Hash Maps, Heap, Trie, Stack, Queue
- **Algorithms** — Two Pointers, Sliding Window, Binary Search, BFS / DFS, Dynamic Programming, Backtracking, Greedy, Bit Manipulation
- **Design** — LRU Cache, Randomized Set, Trie, Linked List Design
- **Database** — SQL JOINs, Subqueries, Aggregation Functions

---

## 🚀 Running Solutions

```bash
# Python
python algorithms/clone_graph.py

# Go
go run algorithms/squares_of_sorted_array.go
```

---

## 📝 Solution Format

Each file includes a link to the original LeetCode problem and an optimized solution:

```python
# https://leetcode.com/problems/single-number/
class Solution:
    def singleNumber(self, numbers: List[int]) -> int:
        xor_sum = 0
        for number in numbers:
            xor_sum = xor_sum ^ number
        return xor_sum
```

---

## 🏆 Challenge History

| Challenge | Period | Solved | Status |
|---|---|---|---|
| 🔥 30-Day Challenge | April 2020 | 27 / 30 | 📈 |
| 🌸 May Challenge | May 2020 | 31 / 31 | ✅ |
| ☀️ June Challenge | June 2020 | 21 / 30 | 📈 |
| 🌴 August Challenge | August 2020 | 5 / 31 | 📈 |

---

## 🛠️ Languages Used

- 🐍 **Python** — 299 files
- 🐹 **Go** — 1 file
- 🗄️ **SQL** — 8 files


---

⭐ **Star this repo if you find it helpful!**
