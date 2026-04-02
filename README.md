# Python for LeetCode — Complete Guide

A self-contained, interactive reference guide for engineers who know how to code but need to get up to speed with Python for technical interviews. Built from a Scala/Java engineer's perspective — every concept is explained relative to what you already know.

**Live site → [tarekahmed-mg.github.io/python-leetcode-guide](https://tarekahmed-mg.github.io/python-leetcode-guide)**

---

## What's in it

### Start Here
| Section | What it covers |
|---|---|
| Python 101 | Running Python, types, arithmetic, strings, loops, lists, dicts, sets |
| Python 102 | Functions, lambdas, nested functions, classes, mutability, map/filter/zip |

### Foundations
| Section | What it covers |
|---|---|
| Language Mechanics | Slicing, unpacking, comprehensions, control flow, floor division |
| Collections Deep Dive | list, dict, defaultdict, Counter, deque, heapq, set — internals and key ops |
| Built-ins Arsenal | sorted, bisect, lru_cache, functools — the tools that save lines |

### Core Patterns
| Section | Difficulty |
|---|---|
| Two Pointers | Easy → Hard |
| Sliding Window | Medium |
| Binary Search (incl. search-on-answer) | Medium |
| BFS / DFS | Medium |
| Dynamic Programming (top-down + bottom-up) | Hard |
| Backtracking | Hard |
| Heap / Priority Queue | Medium |

### Data Structures
| Section | What it covers |
|---|---|
| Linked Lists | Reversal, dummy head, fast/slow pointer |
| Trees & Graphs | BST validation, Union-Find, topological sort |
| Tries | TrieNode class, insert/search/startsWith |

### Advanced
| Section | What it covers |
|---|---|
| Bit Manipulation | The 8 tricks you actually need |
| Intervals & Sorting | Merge intervals, min meeting rooms, sweep line |
| Complexity Cheatsheet | DS ops, pattern → complexity, input size → algorithm |

---

## Features

- **Syntax-highlighted code** — GitHub-dark theme with colour-coded keywords, builtins, comments, and strings
- **Scala callout boxes** — every major concept explained relative to Scala/Java equivalents
- **Gotcha warnings** — the Python traps that catch engineers from typed languages (floor division, mutability, recursion limits, 2D matrix references)
- **Scrollspy sidebar** — jump to any section instantly
- **Complexity boxes** — time and space per pattern
- **Zero dependencies** — single HTML file, no build step, no framework

---

## Running locally

```bash
git clone https://github.com/TarekAhmed-MG/python-leetcode-guide.git
cd python-leetcode-guide
open index.html   # Mac
# or just drag index.html into your browser
```

No install. No server. Just open the file.

---

## Curriculum this pairs with

Built to complement the [Neetcode 150](https://neetcode.io/practice) problem set. The section order mirrors the recommended study order:

1. Start with 101/102 if Python is new to you
2. Two Pointers + Sliding Window → first 30 problems
3. Binary Search + BFS/DFS → next 40
4. DP + Backtracking → the hard problems
5. Heap + Tries + Graphs → round out the set
6. Bit Manipulation + Intervals → fill the gaps

---

## Stack

Pure HTML/CSS/JS — intentionally no framework so it can be dropped anywhere and opened offline. Fonts loaded from Google Fonts CDN.
