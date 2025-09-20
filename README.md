# AI-DFS-BFS
Implementation of 8-Puzzle Problem using Breadth First Search (BFS) and Depth First Search (DFS) algorithms for AI Lab Assignment 1. Includes Python code, detailed explanation, and comparison of BFS vs DFS.


# 🎯 AI Lab Assignment 1: 8-Puzzle Problem using BFS & DFS

**Student:** Saket Kumar  
**Institute:** IIT Patna  
---

## 🚀 Project Overview
This repository contains a complete solution to the **8-Puzzle Problem**, implemented using two fundamental **search algorithms** in Artificial Intelligence:  

- **Breadth First Search (BFS)**  
- **Depth First Search (DFS)**  

The main goal is to move the **blank space ('B')** in a 3×3 grid to reach the **target arrangement**:

```

1 2 3
4 5 6
7 8 B

```

The project demonstrates how BFS and DFS explore the state space differently, compares their efficiency, and highlights their strengths and weaknesses.

---

## 💡 Key Features
- ✅ **Random 3×3 puzzle generator** for start state.  
- ✅ **BFS implementation** guarantees the shortest path to the solution.  
- ✅ **DFS implementation** explores deeper paths, useful for memory-efficient search.  
- ✅ **Step comparison** between BFS and DFS for any start state.  
- ✅ **Intuitive explanations** embedded in the notebook.  

---

## 📊 BFS vs DFS: Quick Comparison

| Feature                  | BFS                                      | DFS                                     |
|---------------------------|-----------------------------------------|----------------------------------------|
| Exploration Strategy      | Level by level                          | Deep-first path exploration            |
| Path Optimality           | Always finds the shortest path          | May not find the shortest path         |
| Memory Usage              | High                                     | Low                                     |
| Time to Find Solution     | Consistent, optimal                     | Can be faster or slower depending on path |
| Best Use Case             | When correctness and optimality matter  | When memory is limited or deep paths may contain solutions |

---

## 🧩 How to Use
1. Open the notebook `2312res560.ipynb` in **Google Colab** or **Jupyter Notebook**.  
2. Run all cells sequentially.  
3. Observe the **random start grid**, **target grid**, and BFS/DFS step counts.  
4. Read the detailed markdown explanations for a clear understanding of the algorithms.  

---

## 🔍 Insights & Observations
- **BFS** ensures the **shortest path solution** and is reliable for correctness.  
- **DFS** can reach a solution faster in some rare cases, but the path may not be optimal.  
- The project highlights the **trade-offs between memory usage, solution optimality, and search depth** in AI problem-solving.

---

## 📁 Repository Structure
```

AI-Lab-Assignment1-DFS-BFS/
│
├── 2312res560.ipynb       # Main Colab notebook with code and explanations
├── README.md              # Project overview, instructions, and comparisons

```

---

## 🌟 Conclusion
This project demonstrates **practical AI search strategies** on the 8-puzzle problem. It provides a clear comparison between BFS and DFS, showing **when to prefer one over the other**, and helps understand key AI concepts such as **state-space exploration, optimality, and algorithm efficiency**.  

---

**Made with ❤️ by Saket Kumar | IIT Patna**
```
