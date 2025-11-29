# Assignment 9 – Graphs  
This README summarizes all programs included in **Assignment 9**, covering graph creation, traversal, MST algorithms, and shortest path algorithms.

Source reference: Assignment file fileciteturn1file0

---

## 1. Graph Using Adjacency Matrix  
Features:  
- Add edge  
- Remove edge  
- In-degree  
- Out-degree  
- Adjacent vertices  
- Count edges  
- Display adjacency matrix  

Includes a menu-driven program.

---

## 2. Breadth-First Search (BFS)  
Implements BFS using an adjacency matrix and a simple queue.  
User inputs vertices, edges, and a starting node.

---

## 3. Depth-First Search (DFS)  
Recursive DFS implementation with adjacency matrix.  
Includes DFSUtil helper for recursion.

---

## 4. Kruskal’s Minimum Spanning Tree  
Uses:  
- Disjoint Set (Union-Find)  
- Sorting edges by weight  
- Constructing MST  
Outputs chosen edges and total MST cost.

---

## 5. Prim’s Minimum Spanning Tree  
Uses adjacency matrix and arrays:  
- key[]  
- parent[]  
- inMST[]  

Prints MST edges and total weight.

---

## 6. Dijkstra’s Algorithm  
Computes shortest path from a given source to all vertices.  
Uses adjacency matrix and:  
- dist[]  
- visited[]  

Prints vertex-wise shortest distances.

---

## How to Run  
1. Put each program in its own `.cpp` file.  
2. Compile:
   ```
   g++ filename.cpp -o output
   ```
3. Run:
   ```
   ./output
   ```

---

## Author  
Generated README for the provided Assignment 9 solutions.

