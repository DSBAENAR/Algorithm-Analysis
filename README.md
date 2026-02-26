# DSA & Analysis

This repository contains my notes and implementations related to Data Structures and Algorithms (DSA) as well as their analysis. It serves as a resource for students, developers, and anyone interested in learning about DSA concepts, algorithms, and their complexities.

## Contents

### Big O Notation — [`BigONotation/firstSteps.ipynb`](BigONotation/firstSteps.ipynb)

An interactive notebook covering:

- **What is Big O Notation?** — Definition and simplification rules
- **Matrix iteration example** — Walkthrough of an O(n²) algorithm
- **Python Standard Collections** — Time complexity analysis of:
  - **List** — Dynamic array operations and benchmarks
  - **Dict** — Hash table key-value operations
  - **Set** — Hash-based membership testing and set operations
  - **Deque** — Double-ended queue from `collections`
- **Comparison table** — When to use each data structure
- **Exercises** (brute force vs optimized, with Big O analysis):

  | # | Problem | Brute Force | Optimized | Key Structure |
  |---|---------|-------------|-----------|---------------|
  | 1 | Find Duplicates | O(n²) | O(n) | Set |
  | 2 | Two Sum | O(n²) | O(n) | Dict |
  | 3 | BFS Traversal | O(V·(V+E)) | O(V+E) | Deque |
  | 4 | Frequency Counter | O(n·k) | O(n) | Dict |
  | 5 | Sliding Window Max | O(n·k) | O(n) | Deque |

## References

- [Python Wiki — TimeComplexity](https://wiki.python.org/moin/TimeComplexity)
