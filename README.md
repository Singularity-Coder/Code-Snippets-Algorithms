![alt text](https://github.com/Singularity-Coder/Code-Snippets-Algorithms/blob/main/assets/banner_algorithm.png)
# Code Snippets Algorithms
List of Algorithm topics and their code snippets!

## Algorithm Analysis

## Linked List

## Stack and Queue

## Recursion

## Binary Tree

## Binary Search Tree

## Heap

## Sorting
#### Bubble Sort
* Bubble sort a.k.a Sinking Sort
* Steps
	* Traverse Array from 1st to last element
	* Compare current element with next element
	* if current element > next element -> swap each other's position
	* Step 4 is repeated until whole list is sorted. Ascending or descending depends on condition.
* Very slow algorithm especially for large unsorted lists
* Complexity
	* Worst (t) = O(n^2) - Since 2 for-loops nested. Where "n" is the list size.
	* Avg (t) = O(n^2) - Since 2 for-loops nested. Where "n" is the list size.
	* Best (t) = O(n) - Since list is sorted.
	* Space (s) = O(1) - Since we are performing inplace operations (meaning modifying the input list itself). No additional DS or variables used.
#### Insertion Sort
#### Quick Sort
#### Selection Sort

## Searching
#### Linear Search
#### Binary Search
* Also known as Half-Interval Search, Logarithmic Search, Binary Chop.
* Elements in the array must be sorted before searching.
* This divides the search inetrval in falf.
* If the search value is less than the middle item of the interval, narrow the interval to the lower half. Else narrow it to upper half
* Repeatedly check until the search value is found or the interval is empty
* In case of binary search, array elements must be in ascending order.


## Hashing

## AVL Tree

## Threaded Binary Tree

## Expression Tree

## B Tree

## Graph
* Adjacency matrix
* Adjacency list
* Path matrix
* Warshall’s Algorithm
#### Traversal in Graph
* Breadth First Search (BFS) 
* Depth First Search (DFS)
#### Shortest Paths in Graph
* Dijkstra’s Shortest Path Algorithm
#### Minimum Spanning Tree of a Graph
* Prim's Algorithm  
* Kruskal's Algorithm 