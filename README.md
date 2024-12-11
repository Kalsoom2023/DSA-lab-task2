# DSA-lab-task2 Lab 2: Sorting Algorithms

## Overview
Lab 2 focuses on implementing and understanding fundamental sorting algorithms. Sorting is a crucial operation in data structures and algorithms, widely used in computer science applications to organize data in a specific order (ascending or descending). This lab will cover a variety of sorting techniques, including their principles, implementation, and performance analysis.

---

## Learning Objectives
1. Understand the basic concepts of sorting algorithms.
2. Implement different sorting algorithms in code.
3. Analyze the time and space complexity of sorting algorithms.
4. Compare the efficiency of various sorting techniques under different scenarios.

---

## Sorting Algorithms Covered
1. *Bubble Sort*
   - Compares adjacent elements and swaps them if they are in the wrong order.
   - Time Complexity:
     - Worst Case: O(n^2)
     - Best Case: O(n) (when the array is already sorted).
   - Space Complexity: O(1) (in-place sorting).

2. *Selection Sort*
   - Finds the smallest element in the array and places it at the beginning.
   - Time Complexity:
     - Worst and Best Case: O(n^2).
   - Space Complexity: O(1).

3. *Insertion Sort*
   - Builds the sorted array one element at a time by inserting each element into its correct position.
   - Time Complexity:
     - Worst Case: O(n^2).
     - Best Case: O(n) (when the array is already sorted).
   - Space Complexity: O(1).

4. *Merge Sort*
   - Divides the array into halves, recursively sorts them, and merges the sorted halves.
   - Time Complexity: O(n log n).
   - Space Complexity: O(n).

5. *Quick Sort*
   - Divides the array using a pivot and recursively sorts the partitions.
   - Time Complexity:
     - Worst Case: O(n^2) (when the pivot selection is poor).
     - Average Case: O(n log n).
   - Space Complexity: O(log n) (for recursion stack).

---

## Tasks
1. Implement each sorting algorithm in your preferred programming language.
2. Test the algorithms on arrays of various sizes and compositions (sorted, reverse sorted, random).
3. Measure the runtime for each algorithm and compare their performance.
4. Identify and explain the scenarios where each sorting algorithm performs best.

---

## Files Included
- *sorting_algorithms.py*: Contains the implementation of all sorting algorithms.
- *test_cases.txt*: Includes sample input arrays for testing the sorting algorithms.
- *results.csv*: Stores the runtime comparisons of different algorithms.

---

## How to Run
1. Clone the repository or download the lab files.
2. Navigate to the folder containing the code.
3. Execute the Python script to see the sorting results:
   bash
   python sorting_algorithms.py
   
4. View the runtime comparisons in the results.csv file.

---

## Expected Output
1. Correctly sorted arrays for all test cases.
2. Runtime comparison for sorting algorithms.
3. A brief summary explaining the performance differences.

---

## Additional Notes
- Pay special attention to edge cases like empty arrays or arrays with duplicate elements.
- Use debugging and logging to understand the inner workings of each algorithm.
- Try to optimize your code for better performance where applicable.



---
