
# Assignment 7 – Sorting Algorithms

This assignment covers several classical and advanced sorting algorithms, each implemented in C++.

## 1. Basic Sorting Algorithms
### a) Selection Sort  
- Finds the minimum element and places it at the beginning  
- Repeats for each position  

### b) Insertion Sort  
- Builds a sorted array one element at a time  
- Shifts elements to insert each value  

### c) Bubble Sort  
- Compares adjacent elements and swaps if needed  
- Repeated passes push the largest element to the end  

### d) Merge Sort  
- Uses divide‑and‑conquer  
- Splits array, sorts halves, merges them  

### e) Quick Sort  
- Uses partitioning around a pivot  
- Recursively sorts partitions  

---

## 2. Improved Selection Sort
Simultaneously finds:
- Minimum from left side  
- Maximum from right side  
Reduces number of passes by handling two values per iteration.

---

## 3. Counting Sort
- Counts occurrences of each element  
- Displays count array  
- Builds sorted array using counts  

---

## 4. Radix Sort (with Counting Sort as sub‑routine)
- Sorts by each digit (exp = 1,10,100…)  
- Uses stable counting sort for each digit  
- Shows intermediate sorting steps after each digit pass  

---

## How to Compile and Run
```
g++ filename.cpp -o output
./output
```

## Author
Nishant Bimra
