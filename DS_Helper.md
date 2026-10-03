# Data Structures (BCS301) — Study Priority Guide
*Based on frequency analysis of PYQs from 2019-20 to 2025-26 (6 papers, 141 questions)*

---

## UNIT I — Introduction to Data Structures
**High Priority (appeared almost every year):**
- Asymptotic Notation / Time & Space Complexity / Big-O — appears in **every single year**, in Section A or C. Easiest guaranteed marks.
- Multidimensional Array Address Calculation (Row Major / Column Major) — appears in **5 of 6 years**, almost always a numerical problem in Section B/C. Practice at least 3-4 variations.
- Recursion (Tail Recursion, Iteration vs Recursion, Tower of Hanoi) — appears in **every year** in some form.

**Medium Priority:**
- Sparse Matrix representation.
- Classification of Data Structures / Linear vs Nonlinear.

**Low Priority / Rarely Asked:**
- Pointer arrays, record structures — no direct PYQ found; know definitions only.

**Quick Insight:** This unit is "safe scoring" territory — mostly short-answer/numerical, low effort-to-marks ratio. Master array address formulas and asymptotic notation comparisons first.

---

## UNIT II — Stacks & Queues
**High Priority:**
- Infix → Postfix Conversion (and evaluation using stack) — the **single most repeated long-answer question** across all 6 years. Practice the standard expression `A+(B*C-(D/E^F)*G)*H` — it has appeared verbatim multiple times.
- Stack implementation (array/linked list), Push/Pop operations.
- Circular Queue & Dequeue — recurring Section A/C topic.

**Medium Priority:**
- Balanced parentheses checking using stack.
- Priority Queue (definition/significance).

**Quick Insight:** If you only prepare one long-answer topic from this unit, make it **infix-to-postfix conversion with trace** — it's nearly guaranteed. Also revise stack-based applications (expression evaluation, parentheses matching, string reversal).

---

## UNIT III — Linked Lists
**High Priority:**
- Polynomial Representation & Addition using Linked List — appears in **4 of 6 years**, almost always a full long-answer (algorithm + C code).
- Singly vs Doubly Linked List — advantages/disadvantages comparisons appear repeatedly.

**Medium Priority:**
- Linked list vs Array trade-offs.
- Insert/delete node operations, concatenation of lists.

**Low Priority:**
- Circular Linked List, Dynamic Memory Allocation — no direct PYQs found; cover briefly for conceptual (Section A) questions only.

**Quick Insight:** This is the **smallest unit by question volume**, but polynomial representation is a near-certain long question — don't skip the C code for it.

---

## UNIT IV — Trees & Graphs
**This is the heaviest-weighted unit — expect 3-4 Section C questions from here.**

**High Priority:**
- Tree construction from given traversals (Inorder+Preorder/Postorder → find the third) — recurring long-answer.
- Binary Search Tree (construction, search, BST vs Heap) — appears almost every year.
- AVL Tree construction by insertion — appears in **4+ years**, often with the *same* number sequence (71,41,91,56,60,30,40,80,50,55) repeated across 2024-25 and 2025-26.
- B-Tree construction/insertion/deletion (order 4 or 5) — recurring, with the same letter sequence (`agfbkdhmjesirxclntup`) reused across years.
- Minimum Spanning Tree — Prim's Algorithm — appears almost every year; Kruskal's less frequent.
- Shortest Path — Dijkstra's Algorithm — appears almost every year; Floyd-Warshall also recurring.
- Special binary trees (Complete, Extended, Full, Threaded, Skewed) — frequent short-answer definitions.

**Medium Priority:**
- Graph representations (adjacency matrix/list) and terminology.
- BFS/DFS traversal and differences.
- Expression Trees, Huffman Coding.

**Quick Insight:** **Memorize the AVL and B-Tree insertion sequences that repeat across years** — they are reused almost verbatim. Prim's + Dijkstra's are the highest-ROI graph algorithms to practice by hand on a sample graph.

---

## UNIT V — Searching, Sorting & Hashing
**High Priority:**
- Hashing & Collision Resolution (linear probing, quadratic probing, division method) — appears in **every single year**, often as a full long-answer with a numerical example.
- Sorting algorithms with numerical tracing — Quick Sort, Merge Sort, Insertion Sort, Heap Sort all recur; **Quick Sort and Hashing together are the most repeated pairing**.

**Medium Priority:**
- Binary Search (concept, complexity, recursive implementation).
- Selection Sort, Bubble Sort.

**Low Priority:**
- Radix Sort — no PYQs found at all; skip unless time permits.
- Indexed Sequential Search — appeared only once.

**Quick Insight:** Hashing is the **most consistently tested topic in the entire syllabus** — know linear probing, quadratic probing, and the division method cold, including worked numerical examples with insertion sequences.

---

## Overall Exam Strategy
1. **Unit IV (Trees & Graphs)** carries the most long-answer weight — prioritize AVL trees, B-Trees, Prim's, and Dijkstra's.
2. **Hashing (Unit V)** and **Infix-Postfix conversion (Unit II)** are the two most reliably repeated single topics across all 6 years — near-guaranteed questions.
3. **Unit I** and parts of **Unit III** are lower-effort, high-certainty scoring zones — good for last-minute revision.
4. Many numerical questions (AVL insertion sequences, B-Tree letter sequences, infix expressions, array address problems) **repeat near-verbatim across years** — solving past papers directly prepares you for a large share of the actual exam.
