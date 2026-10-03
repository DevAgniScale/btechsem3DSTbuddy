# UNIT IV — Trees & Graphs

---

## Topic: Binary Trees & Tree Traversals (Construction from Given Traversals)
- **[2019-20]** Section C (7.a): Can you find a unique tree when any two traversals are given? Using INORDER: HKDBILEAFCMJG and PREORDER: ABDHKEILCFGJM, construct the corresponding binary tree. Also find the Post Order traversal.
- **[2022-23]** Section B (2.e): The inorder and postorder of a binary tree are: Inorder: B,I,D,A,C,G,E,H,F; Postorder: I,D,B,G,C,H,F,E,A. (i) Draw the corresponding binary tree. (ii) Write the pre order traversal.
- **[2023-24]** Section B (2.d): Write a C function for non-recursive post order traversal.
- **[2024-25]** Section B (2.c): Construct a binary tree with Inorder: B C A E G D H F I J and Preorder: A B C D E G F H I J.

## Topic: Binary Search Trees (BST)
- **[2019-20]** Section B (2.e): What is the difference between a binary search tree (BST) and heap? For a given sequence of numbers, construct a heap and a BST: 34, 23, 67, 45, 12, 54, 87, 43, 98, 75, 84, 93, 31.
- **[2021-22]** Section A (1.c): Draw the binary search tree that results from inserting the following numbers in sequence starting with 11: 11, 47, 81, 9, 61, 10, 12.
- **[2021-22]** Section C (6.a): (i) Write an iterative function to search a key in a Binary Search Tree (BST). (ii) Discuss disadvantages of recursion with a suitable example.
- **[2022-23]** Section A (1.b): Differentiate between binary search tree and a heap.
- **[2024-25]** Section C (6.b): Construct a Binary Search Tree (BST) using the sequence: 50, 30, 70, 20, 40, 60, 80, 35, 45. Perform Inorder traversal.
- **[2025-26]** Section B (2.d): What do you mean by Binary Search Tree? Construct a BST by inserting the sequence: 10, 12, 5, 4, 20, 8, 7, 15 and 13.

## Topic: AVL Trees
- **[2021-22]** Section A (1.h): Write advantages of AVL tree over Binary Search Tree (BST).
- **[2022-23]** Section C (7.a): Discuss left skewed and right skewed binary tree. Construct an AVL tree by inserting: 60, 2, 14, 22, 13, 111, 92, 86.
- **[2024-25]** Section B (2.d): Construct an AVL Tree by inserting the sequence: 71, 41, 91, 56, 60, 30, 40, 80, 50, 55.
- **[2025-26]** Section C (6.b): Insert the sequence of elements into an AVL tree, starting with an empty tree: 71, 41, 91, 56, 60, 30, 40, 80, 50, 55.

## Topic: Special Binary Trees (Complete, Extended, Full, Strictly Binary, Threaded, Skewed, Expression Tree, Huffman Coding)
- **[2019-20]** Section A (1.i): Define extended binary tree, full binary tree, strictly binary tree and complete binary tree.
- **[2019-20]** Section A (1.j): Explain threaded binary tree.
- **[2021-22]** Section B (2.e): What is the significance of maintaining threads in a Binary Search Tree? Write an algorithm to insert a node in a threaded binary tree.
- **[2022-23]** Section A (1.e): Construct an expression tree for the algebraic expression: (a-b)/((c*d)+e).
- **[2022-23]** Section A (1.i): In a complete binary tree if the number of nodes is 1,000,000, what will be the height of the complete binary tree?
- **[2023-24]** Section A (1.e): What is the significance of binary tree in Huffman algorithm?
- **[2023-24]** Section C (6.a): If E and I denote the external and internal path length of a binary tree having n internal nodes, show that E = I + 2n.
- **[2023-24]** Section C (6.b): Characters a,b,c,d,e,f have given probabilities. Find an optimal Huffman code and draw the Huffman tree. What is the average code length?
- **[2024-25]** Section A (1.g): Illustrate the significance of Threaded Binary Tree.
- **[2025-26]** Section A (1.e): Explain the term Complete Binary Tree.
- **[2025-26]** Section C (6.a): Write short notes on the following: (a) Binary Search Trees (b) Complete Binary Tree (c) Extended Binary Tree.

## Topic: B-Trees
- **[2019-20]** Section C (7.b): What is a B-Tree? Generate a B-Tree of order 4 with the letters arriving in the sequence: agfbkdhmjesirxclntup.
- **[2021-22]** Section C (7.a): (i) Why is the time complexity of search operation in B-Tree better than BST? (ii) Insert given keys into an initially empty B-tree of order 5. (iii) What is the resultant B-Tree after deleting keys j, t and d in sequence?
- **[2022-23]** Section C (7.b): What is B-Tree? Write the various properties of B-Tree. Show the results of inserting the keys F,S,Q,K,C,L,H,T,V,W,M,R,N,P,A,B in order into an empty B-Tree of order 5.
- **[2024-25]** Section C (6.a): Demonstrate B-Tree? Construct a B-Tree of order 4 with letters arriving in sequence: agfbkdhmjesirxclntup.

## Topic: Graph Representations & Terminology (Adjacency Matrix/List, Degree, Connectivity, etc.)
- **[2019-20]** Section A (1.h): Compare adjacency matrix and adjacency list representations of graph.
- **[2021-22]** Section A (1.j): Write different representations of graphs in the memory.
- **[2023-24]** Section A (1.f): What is the number of edges in a regular graph of degree d and n vertices?
- **[2023-24]** Section A (1.g): Write an algorithm to obtain the connected components of a graph.
- **[2023-24]** Section C (7.b): Write a program in C language to compute the indegree and outdegree of every vertex of a directed graph when represented by an adjacency matrix.
- **[2024-25]** Section C (7.a): Explain two ways to represent a graph in memory and compare their advantages: (i) Adjacency matrix (ii) Adjacency List.
- **[2024-25]** Section C (7.b): Explain the following graph terminologies with examples: (i) Graph (ii) Weighted Graph (iii) Degree of a Vertex (iv) Connected and Disconnected Graph (v) Cycle in a Graph (vi) Directed and Undirected Graph (vii) MST.

## Topic: Graph Traversals (BFS, DFS)
- **[2021-22]** Section B (2.c): Differentiate between DFS and BFS. Draw the Breadth First Tree for the given graph.
- **[2022-23]** Section A (1.h): Write an algorithm for Breadth First Search (BFS) traversal of a graph.
- **[2024-25]** Section B (2.e): Explain the Depth-First Search (DFS) algorithm with the help of an example graph. Which data structure is used for DFS and BFS?

## Topic: Minimum Spanning Tree (Kruskal's & Prim's Algorithm)
- **[2019-20]** Section A (1.g): What is Minimum cost spanning tree? Give its applications.
- **[2019-20]** Section B (2.d): Find the minimum spanning tree in the given graph using Kruskal's algorithm.
- **[2021-22]** Section C (5.b): Apply Prim's algorithm to find a minimum spanning tree in the given weighted graph.
- **[2022-23]** Section C (6.a): What is spanning tree? Write down Prim's algorithm to obtain minimum cost spanning tree. Use it to find the MST in the given graph.
- **[2023-24]** Section C (7.a): Find the minimum spanning tree using Prim's algorithm for the given graph.
- **[2025-26]** Section A (1.g): Define the Minimum spanning tree.
- **[2025-26]** Section C (7.a): Use Prim's Algorithm to compute MST for the given weighted graph.

## Topic: Shortest Path Algorithms (Dijkstra's, Floyd-Warshall, Warshall's)
- **[2019-20]** Section C (6.a): Explain Warshall's algorithm with the help of an example.
- **[2019-20]** Section C (6.b): Describe the Dijkstra algorithm to find the shortest path. Find the shortest path in the given graph with vertex "S" as source.
- **[2021-22]** Section C (5.a): Use Dijkstra's algorithm to find the shortest paths from source to all other vertices in the given graph.
- **[2022-23]** Section B (2.d): Write the Dijkstra algorithm for shortest path and find the shortest path from 'S' to all remaining vertices in the given graph.
- **[2022-23]** Section C (6.b): Write and explain the Floyd Warshall algorithm to find the all-pair shortest path. Use it to find shortest paths among all vertices in the given graph.
- **[2023-24]** Section B (2.e): Consider the given graph and using Dijkstra Algorithm find the shortest path.
- **[2025-26]** Section C (7.b): Write and explain the Floyd Warshall algorithm to find the all-pair shortest path. Use it to find the shortest path among all vertices in the given graph.
