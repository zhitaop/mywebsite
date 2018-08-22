---
title: "Algorithms"
date: 2018-08-01T23:11:51+10:00
draft: true
---
#### https://visualgo.net/en

### - Data structure
* Array
* Linked list
* Stack (LIFO)
* Queue (FIFO) 
* Priority queue
* Tree
* Graph

### - Growth rate and Analysis
* Time and space complexty

    t(n) ≈ c·g(n)
    where c is the cost of a basic operation and g is the number of times the operation is performed in terms of input size n.
* Best, worst and average case 
* f (n) ≺ g(n) iff lim[n ->infinity] f(n)/g(n) = 0
* 1 ≺ log n ≺ n^e ≺ n^c ≺ n^(log n) ≺ c^n ≺ n^n  
where 0 < e < 1 < c
* Big-O, Big-Omega and Big-Theta 
* Complexity Analysis

### - Brute Force
* Selection Sort
* String Matching
* Closest pair
* Exhaustive search for combinatorial problem
* Graph traversal


### - Recursion
* Example: Factorial Numbers and Fibonacci Numbers
* Example: Tower of Hanoi
* General guideline for recursion: recursively divide the problem into smaller sub-problems until base cases are reached.
* More efficient solution for recursion: dynamic programming


### - Graph
* Graph concepts: Undirected - directed, Connnected - Not connected, Unweighted- weighted, Dense - Sparse, Cyclic - Acyclic(a tree), Directed cyclic - Directed acyclic(a dag)
* The degree of node v is the number of edges incident on v.
* Mathematical representation of graph: 

![alt text](/graphinmath.PNG "graph")

* Graph representations : adjacency matrix and adjacency list

### - Decrease and Conquer by constant
* The problem is reduced by some constant in each iteration of the algorithm
* To solve a problem of size n, try to express the solution in terms of a solution to the same problem of size n − 1.
* Insertion sort
* The trick of posting a sentinel for insertion sort
* Shellsort

### - Decrease and Conquer by factor
* Decrease-by-a-constant-factor: Binary search
* Decrease-by-a-variable-factor: Interpolation search
* Lomuto Partitioning

### - Divide and Conquer
* 
  1. Divide the given problem instance into smaller instances. 
  2. Solve the smaller instances recursively.
  3. Combine the smaller solutions to solve the original instance.
* The Master Theorem
* Mergesort
* Quicksort and corresponding improvements:
 * Median-of-three
 * Early Cut-off

### Binary Tree
* Binary tree traversal:
 * Preorder: root -> left subtree -> right subtree
 * Inorder: left subtree -> root -> right subtree
 * Postorder: left subtree -> right subtree -> root
 * Level-order: visits the nodes level by level, starting from the root
* Closest Pair problem using divide-and-conquer to reach theta(nlogn) complexity

### - Heap and Heap sort
* A Heap is a complete binary tree which satisfies the heap condition: <br>Each child has priority no greater than its parent's.(a max-heap)
*
* Heapsort: Given unsorted array H[1..n]:
    1. Turn H into a heap
    2. Apply the eject operation n-1 times

### - Transform and conquer
* Try to make the problem easier through pre-processing, typical sorting:
 * Uniqueness checking with presorting
 * Mode finding with presorting
 * Searching with presorting
* Binary Search Tree: <br>Each element in the left subtree is smaller than the root, and each element in the right sub-tree is larger than the root
 * BST which is "reasonably" balanced involves Theta(logn) comparisons in the worst case.
 * BST which is not balanced involves linear search in the worst case.
 * To insert a new element into a BST, search for k and insert the element at the empty sub-tree.

### - Balanced tree
* AVL tree:
 * balance factor: the difference between the height of left subtree and right subtree.
 * An AVL tree is a BST in which the balance factor is -1, 0 or 1 for every sub-tree.
 * Insertion: transform the tree to regain balance after insertion by rotations.
 * R-Rotation, L-Rotation, RL-Rotation, LR-Rotation.
 * Always rebalance the lowest unbalanced subtree.
 * Some more balanced tree:
  * Red-black tree
  * splay tree
* 2-3 Trees and 2-3-4 Trees
 * A node that holds a single item has aat most two children.
 * A node that holds two items has at most three children, and etc.
 

### - Time space tradeoff

### - Hashing

### - Dynamic Programming

### - Warshall and Floyd

### - Greedy Algorithms

### - NP Completeness
