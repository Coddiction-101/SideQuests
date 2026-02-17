# ⚙️ C++ Learning Roadmap

A complete, structured roadmap to learn C++ from scratch — focused on DSA, real-world projects, and building independently. Concept-first, project-driven, no fluff.

---

## 🎯 Goal
Master C++ well enough to:
- Solve DSA problems confidently
- Build real-world console applications independently
- Understand memory, pointers, and OOP deeply
- Be interview and competitive programming ready

---

## ⚡ Setup
```
Compiler    g++ (MinGW on Windows / g++ on Linux/Mac)
Editor      VS Code + C/C++ Extension
Standard    C++17
Version     g++ -std=c++17 file.cpp -o output
Online IDE  https://onlinegdb.com (for quick practice)
```

---

## ❌ What to Skip (Don't Waste Time)

| Topic | Reason |
|---|---|
| Turbo C++ / Old compilers | Outdated, irrelevant |
| `printf` / `scanf` | Use `cout` / `cin` |
| C-style strings (`char[]`, `strcpy`) | Use `string` class |
| `goto` statements | Bad practice |
| `NULL` pointer | Use `nullptr` |
| `register` keyword | Compiler ignores it |
| Complex multiple inheritance | Overused, avoid |
| `union` types | Rarely used |
| Graphics.h | Outdated graphics library |
| Bitwise ops (early) | Learn only when needed for CP |
| Templates (early) | Learn after solid OOP foundation |
| Multithreading (early) | Advanced, learn after DSA |

---

## 📅 Phase 1 — Foundations
> **Goal:** Write clean C++ programs with full control flow and functions

### Block 1: Basics & I/O
- [ ] Program structure (`#include`, `main()`, `return 0`)
- [ ] `cout`, `cin`, `endl`
- [ ] Data types: `int`, `float`, `double`, `char`, `bool`, `string`
- [ ] Variables, constants (`const`, `#define`)
- [ ] Operators: arithmetic, relational, logical, assignment
- [ ] Type casting: `int(x)`, `static_cast<int>(x)`
- [ ] Comments: `//` and `/* */`

### Block 2: Control Flow
- [ ] `if`, `else if`, `else`
- [ ] Ternary operator: `condition ? a : b`
- [ ] `switch-case`
- [ ] Comparison & logical operators
- [ ] Nested conditions

### Block 3: Loops
- [ ] `for` loop
- [ ] `while` loop
- [ ] `do-while` loop
- [ ] `break` and `continue`
- [ ] Nested loops
- [ ] Loop patterns (pyramid, diamond, number patterns)

### Block 4: Functions
- [ ] Function declaration & definition
- [ ] Parameters & return types
- [ ] Pass by value vs pass by reference (`&`)
- [ ] Function overloading
- [ ] Default parameters
- [ ] `void` functions
- [ ] Recursion basics (factorial, fibonacci)

### Block 5: Arrays & Strings
- [ ] 1D arrays: declaration, traversal, operations
- [ ] 2D arrays: matrix operations
- [ ] `string` class: `.length()`, `.substr()`, `.find()`, `+=`
- [ ] String traversal and manipulation
- [ ] Array sorting (bubble, selection, insertion)

**✅ Phase 1 Project:** Personal Bio Card Generator

---

## 📅 Phase 2 — Intermediate Concepts
> **Goal:** Understand memory, OOP, and the STL

### Block 6: Pointers & References
- [ ] What are pointers (`*`, `&`)
- [ ] Pointer arithmetic
- [ ] Pointers with arrays
- [ ] References vs pointers
- [ ] `nullptr` (not `NULL`)
- [ ] Dynamic memory: `new` and `delete`
- [ ] Memory leaks and prevention

### Block 7: OOP — Basics
- [ ] `struct` for grouping data
- [ ] `class`: `public`, `private`, `protected`
- [ ] Constructors & destructors
- [ ] Member functions
- [ ] `this` pointer
- [ ] Getters & setters (encapsulation)
- [ ] Object arrays

### Block 8: OOP — Advanced
- [ ] Inheritance: `public`, `protected`, `private`
- [ ] Method overriding
- [ ] Virtual functions & polymorphism
- [ ] Abstract classes & pure virtual functions
- [ ] Constructor chaining (`parent::`)
- [ ] Copy constructor

### Block 9: STL — The Game Changer
- [ ] `vector<T>`: push_back, pop_back, size, access
- [ ] `pair<T1,T2>` and `tuple`
- [ ] `map<K,V>` and `unordered_map<K,V>`
- [ ] `set` and `unordered_set`
- [ ] `stack<T>` and `queue<T>`
- [ ] `deque` and `priority_queue`
- [ ] Iterators: `.begin()`, `.end()`
- [ ] Algorithms: `sort()`, `find()`, `reverse()`, `min()`, `max()`
- [ ] `auto` keyword
- [ ] Range-based for: `for(auto x : vec)`

**✅ Phase 2 Projects:**
- Task Manager & Scheduler ✅
- Banking System - ATM Simulator ✅

---

## 📅 Phase 3 — DSA Fundamentals
> **Goal:** Solve problems with the right data structure and algorithm

### Block 10: Complexity Analysis
- [ ] Big O notation: O(1), O(n), O(log n), O(n²)
- [ ] Analyzing loops and nested loops
- [ ] Best, average, worst case
- [ ] Space complexity basics
- [ ] Why complexity matters

### Block 11: Searching & Sorting
- [ ] Linear search
- [ ] Binary search (on sorted arrays)
- [ ] Bubble sort
- [ ] Selection sort
- [ ] Insertion sort
- [ ] Merge sort (divide & conquer)
- [ ] Quick sort
- [ ] STL `sort()` with comparators
- [ ] When to use which algorithm

### Block 12: Recursion & Backtracking
- [ ] Recursion fundamentals
- [ ] Base case & recursive case
- [ ] Call stack visualization
- [ ] Recursion vs iteration
- [ ] Classic problems: factorial, fibonacci, power
- [ ] Tower of Hanoi
- [ ] Backtracking pattern
- [ ] Subsets & permutations

### Block 13: Linked Lists
- [ ] Node structure
- [ ] Singly linked list: insert, delete, traverse, search
- [ ] Doubly linked list
- [ ] Circular linked list
- [ ] Reverse a linked list
- [ ] Detect cycle (Floyd's algorithm)
- [ ] Merge two sorted lists

### Block 14: Stacks & Queues
- [ ] Stack: LIFO, push, pop, top, isEmpty
- [ ] Queue: FIFO, enqueue, dequeue, front
- [ ] Implement using arrays & linked lists
- [ ] Applications: balanced parentheses, undo/redo
- [ ] Monotonic stack
- [ ] Deque (double-ended queue)
- [ ] Priority queue (min/max heap)

### Block 15: Trees
- [ ] Binary tree structure & terminology
- [ ] Tree traversals: inorder, preorder, postorder, level-order
- [ ] BST: insert, search, delete
- [ ] Height & depth of tree
- [ ] AVL tree (balanced BST concept)
- [ ] Min-heap & max-heap
- [ ] Heap sort

### Block 16: Graphs
- [ ] Graph representation: adjacency list, adjacency matrix
- [ ] BFS (Breadth-First Search)
- [ ] DFS (Depth-First Search)
- [ ] Cycle detection
- [ ] Topological sort
- [ ] Shortest path: Dijkstra's algorithm
- [ ] MST: Kruskal's & Prim's (basics)

**✅ Phase 3 Projects:**
- File Organizer 🔨
- Sorting Visualizer (text-based)
- Maze Generator & Solver

---

## 📅 Phase 4 — Advanced Concepts
> **Goal:** Solve hard problems and build advanced projects

### Block 17: Dynamic Programming
- [ ] Memoization (top-down)
- [ ] Tabulation (bottom-up)
- [ ] Classic problems: fibonacci, knapsack, coin change
- [ ] Longest Common Subsequence (LCS)
- [ ] Longest Increasing Subsequence (LIS)
- [ ] DP on grids
- [ ] When to recognize a DP problem

### Block 18: File Handling
- [ ] `fstream`, `ifstream`, `ofstream`
- [ ] Read & write text files
- [ ] Binary file mode
- [ ] Custom delimiters for parsing
- [ ] Error handling with files

### Block 19: Exception Handling
- [ ] `try`, `catch`, `throw`
- [ ] Standard exceptions
- [ ] Custom exception classes
- [ ] RAII principle
- [ ] Exception safety

### Block 20: Modern C++ (C++11/17)
- [ ] Smart pointers: `unique_ptr`, `shared_ptr`
- [ ] Lambda functions: `[](int x){ return x*2; }`
- [ ] `auto` and type inference
- [ ] Range-based for loops
- [ ] Structured bindings
- [ ] `<filesystem>` library (C++17)
- [ ] `<chrono>` for timing
- [ ] `<random>` for random numbers
- [ ] Initializer lists
- [ ] Move semantics (basics)

**✅ Phase 4 Projects:**
- Password Manager
- Expression Calculator
- Resource Monitor

---

## 📅 Phase 5 — Mega Projects
> **Goal:** Build complete, impressive, portfolio-worthy applications

- [ ] Terminal Text Editor
- [ ] Port Scanner & Network Utility
- [ ] Console Snake Game
- [ ] Chess Engine
- [ ] Zombie Survival Simulator

---

## 📊 Overall Progress

| Phase | Topic | Status |
|---|---|---|
| 1 | Basics & I/O | ✅ Done |
| 1 | Control Flow | ✅ Done |
| 1 | Loops | ✅ Done |
| 1 | Functions | ✅ Done |
| 1 | Arrays & Strings | ✅ Done |
| 2 | Pointers & References | 🔨 In Progress |
| 2 | OOP Basics | 🔨 In Progress |
| 2 | OOP Advanced | 📋 Planned |
| 2 | STL | 📋 Planned |
| 3 | Complexity Analysis | 📋 Planned |
| 3 | Searching & Sorting | 📋 Planned |
| 3 | Recursion & Backtracking | 📋 Planned |
| 3 | Linked Lists | 📋 Planned |
| 3 | Stacks & Queues | 📋 Planned |
| 3 | Trees | 📋 Planned |
| 3 | Graphs | 📋 Planned |
| 4 | Dynamic Programming | 📋 Planned |
| 4 | File Handling | ✅ Done |
| 4 | Exception Handling | 📋 Planned |
| 4 | Modern C++ | 📋 Planned |

---

## 🔗 Related Repos
- [cpp-projects](https://github.com/Coddiction-101/cpp_projects) — Built projects
- [cpp-project-ideas](https://github.com/Coddiction-101/cpp-project-ideas) — Project ideas bank
- [DAILY-DSA-CPP](https://github.com/Coddiction-101/DAILY-DSA-CPP) — Daily DSA practice

---

*Updated as each block is completed. Concept first → Practice → Build.*
