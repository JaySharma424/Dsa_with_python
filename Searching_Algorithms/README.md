# 🔍 Searching Algorithms Mastery Guide in Python

Welcome to the **Searching Algorithms Mastery** repository! This repository features a comprehensive, hands-on Google Colab notebook covering fundamental to advanced searching techniques in Python. It includes standard implementations alongside highly modified algorithmic variants designed for real-world data structures and optimization.

---

## 🚀 Algorithms & Variations Covered

### 1. 🚶‍♂️ Linear Search (Sequential Search)
* **Standard Implementation:** Finding a target element in an unsorted array and returning its index ($O(n)$ time complexity).
* **Last Occurrence Finder:** A modified reverse-scan algorithm that skips to the very end of an array containing duplicates to return the absolute last occurrence of a target.
* **Maximum Element Scanner:** Utilizing linear search mechanics to scan unorganized, continuous raw sensor data to extract the maximum value.
* **First Occurrence Utility:** A robust implementation returning the initial index of a target while managing boundary conditions (like empty arrays) gracefully.
* **Accumulator (Frequency Counting):** A conditional counting variant that runs through data (e.g., student grades) to sum up exact match occurrences.
* **Condition-Based Filtering:** Advanced logic that filters and extracts only even numbers strictly greater than 10 into a new collection.

### 2. ⚡ Binary Search (Logarithmic Divide & Conquer)
* **Standard Implementation:** Searching sorted structures with extreme efficiency in $O(\log n)$ time complexity.
* **First Occurrence in Duplicates:** Modified pointer-shifting logic (`right = mid - 1` on match) to find the absolute first occurrence of an element in a duplicate-heavy sorted list.
* **Search Insert Position:** A precise algorithm that returns the index of a target if found, or the exact index where it *should* be inserted to maintain sorted order.
* **Truncated Square Root Finder:** Computing the integer part of $\sqrt{x}$ for a non-negative integer using binary search spaces, completely avoiding built-in math libraries.
* **Peak Index in a Mountain Array:** Finding the turning point (peak) in an array that strictly increases and then strictly decreases in $O(\log n)$ time.
* **Total Occurrence Counter:** Combining first and last boundary binary searches to count exactly how many times a target appears in $O(\log n)$ steps.
* **Minimum in Rotated Sorted Array:** Finding the original minimum/pivot element in a unique array that has been rotated at an unknown index.
* **Search in Rotated Sorted Array:** Dynamically determining which half of a rotated array is normally sorted to successfully hunt down a target index.
* **Perfect Square Verifier:** A logical check that outputs a boolean (`True`/`False`) evaluating if a number is a perfect square without standard exponent tools.

### 3. 🦘 Jump Search (Block Search)
* **Standard Implementation:** An intermediary algorithm for sorted arrays that jumps ahead by fixed steps ($\sqrt{n}$) and then performs a localized linear backward scan to optimize searching with fewer comparisons than traditional linear search.

---

## 💻 Tech Stack
* **Language:** Python 3
* **Environment:** Jupyter Notebook / Google Colab

---

## 🏃‍♂️ How to Run the Notebook

1. Clone this repository to your local profile:
   ```bash
   git clone [https://github.com/JaySharma424/Dsa_with_python.git](https://github.com/JaySharma424/Dsa_with_python.git)
