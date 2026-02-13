## 🔄 Sorting-Algorithms-Techniques
A comprehensive and beginner-friendly collection of sorting algorithms implemented in Java, covering basic, advanced, and optimized techniques widely used in computer science, data science, and real-world systems.

This repository focuses on:

- 📘 Clear explanations
- ⏱️ Time & space complexity comparison
- 🧠 When to use which algorithm
- 🧩 Easy-to-understand Java implementations


![Language](https://img.shields.io/badge/Language-Java-orange)
![DSA](https://img.shields.io/badge/DSA-Sorting-blue)
![Sorting](https://img.shields.io/badge/Topic-Sorting-green)

#### 📂 Algorithms Covered

Bubble Sort  
Selection Sort  
Insertion Sort  
Merge Sort  
Quick Sort  
Heap Sort  
Counting Sort  
Radix Sort  

--- 
## 📊 Time & Space Complexity Comparison

| Algorithm          | Best Case  | Average Case | Worst Case | Space    | Stable |
| ------------------ | ---------- | ------------ | ---------- | -------- | ------ |
| **Bubble Sort**    | O(n)       | O(n²)        | O(n²)      | O(1)     | ✅ Yes  |
| **Selection Sort** | O(n²)      | O(n²)        | O(n²)      | O(1)     | ❌ No   |
| **Insertion Sort** | O(n)       | O(n²)        | O(n²)      | O(1)     | ✅ Yes  |
| **Merge Sort**     | O(n log n) | O(n log n)   | O(n log n) | O(n)     | ✅ Yes  |
| **Quick Sort**     | O(n log n) | O(n log n)   | O(n²)      | O(log n) | ❌ No   |
| **Heap Sort**      | O(n log n) | O(n log n)   | O(n log n) | O(1)     | ❌ No   |
| **Counting Sort**  | O(n + k)   | O(n + k)     | O(n + k)   | O(k)     | ✅ Yes  |
| **Radix Sort**     | O(nk)      | O(nk)        | O(nk)      | O(n + k) | ✅ Yes  |


💡 k = range of input values or number of digits

────────

### 1️⃣ Bubble Sort
Bubble Sort repeatedly compares adjacent elements and swaps them if they are in the wrong order.

⚙️ How It Works

Compare adjacent elements  
Swap if left > right  
Largest element “bubbles” to the end  

✅ Best Used When

Very small datasets  
Already nearly sorted data  
Learning sorting fundamentals  

────────

### 2️⃣ Selection Sort
Selection Sort selects the minimum element and places it at the beginning in each iteration.

⚙️ How It Works

Find the smallest element  
Swap with first unsorted position  
Repeat for remaining array  

✅ Best Used When

Memory writes are costly  
Simple logic required  

────────

### 3️⃣ Insertion Sort
Insertion Sort builds the sorted array one element at a time, like sorting playing cards.

⚙️ How It Works

Pick next element  
Shift larger elements to the right  
Insert element in correct position  

✅ Best Used When

Small datasets  
Nearly sorted arrays  

────────

### 4️⃣ Merge Sort
Merge Sort follows the Divide and Conquer approach.

⚙️ How It Works

Divide array into halves  
Recursively sort each half  
Merge sorted halves  


✅ Best Used When

Large datasets  
Stable sorting required  

────────

### 5️⃣ Quick Sort
Quick Sort selects a pivot element and partitions the array around it.

⚙️ How It Works

Choose a pivot  
Place smaller elements left, larger right  
Recursively sort subarrays  


✅ Best Used When

Fast average-case performance required  
In-place sorting needed  

────────

### 6️⃣ Heap Sort
Heap Sort uses a Binary Heap data structure to sort elements.

⚙️ How It Works

Build a max heap  
Swap root with last element  
Heapify remaining elements  


✅ Best Used When

Guaranteed O(n log n) performance needed  
Memory efficiency matters  

────────

### 7️⃣ Counting Sort
Counting Sort counts occurrences of elements instead of comparing them.

⚙️ How It Works

Count frequency of each value  
Compute prefix sums  
Place elements in correct position  


✅ Best Used When

Integers with small range  
Non-comparison sorting needed  

────────

### 8️⃣ Radix Sort
Radix Sort sorts numbers digit by digit using a stable sub-sorting algorithm.

⚙️ How It Works

Sort by least significant digit  
Move towards most significant digit  


✅ Best Used When

Large numbers  
Fixed-length integers  

---
## 🧠 Which Sorting Algorithm Should I Use?
SituationBest AlgorithmSmall / nearly sorted dataInsertion SortLarge dataset, stable sortMerge SortFast average performanceQuick SortLimited memoryHeap SortIntegers with small rangeCounting SortLarge numbers (digits)Radix Sort

## 🚀 Getting Started
Clone the Repository  
git clone https://github.com/Charanm008/Sorting-Algorithm-Techniques.git  

Navigate to the Project  
cd Sorting-Algorithm-Techniques  

Compile & Run  
javac FileName.java  
java FileName  

________________________________________________________

If this repository helped you understand sorting better,  
consider giving it a ⭐ — it really helps.

Happy Coding 🚀
