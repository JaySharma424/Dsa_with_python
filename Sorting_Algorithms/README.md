# 📊 Sorting Algorithms Mastery Guide in Python

Welcome to the **Sorting Algorithms Mastery** repository! This repository contains a hands-on, practical Google Colab notebook covering essential sorting algorithms in Python. It includes standard implementations along with unique variations, optimization techniques, and real-world problem-solving patterns.

---

## 🚀 Algorithms Covered

### 1. 🫧 Bubble Sort
* **Standard Implementation:** Sorting an array in ascending order with an optimized early-exit condition ($O(n^2)$ worst-case, $O(n)$ best-case).
* **Move Zeros to the Right:** An optimized dual-pointer, in-place variant to segregate zeros and sort non-zero elements without using extra space ($O(1)$ auxiliary space complexity).
* **Strictly Descending Sort:** Re-engineered bubble logic to sort elements from highest to lowest.
* **String Array Sorting:** Custom comparator mechanics to sort an array of strings based on their length.
* **One-Pass Sorted Checker:** A fast $O(n)$ validation utility that runs a single inner loop pass to check if a collection is already sorted.
* **Absolute Difference Sort:** Sorting an array dynamically based on the absolute deviation $|arr[j] - X|$ from a target value $X$.

### 2. 🎯 Selection Sort
* **Standard Implementation:** Finding the minimum element from the unsorted part and putting it at the beginning.
* **Kth Smallest Element:** Finding the $K$-th smallest element in an unsorted array efficiently without executing a full sort.
* **Stable Selection Sort:** Modified logic that preserves the relative initial order of identical elements (converting an inherently unstable sort into a stable one).
* **Maximize Array Sum After K Negations:** A logical puzzle using selection sort mechanics to maximize total array sum by strategically flipping signs.
* **Half-Ascending, Half-Descending Sort:** Splitting and sorting the array structure such that the first half climbs while the second half falls.

### 3. 🃏 Insertion Sort
* **Standard Implementation:** Building a sorted array one item at a time by shifting larger elements to the right.
* **Tuple (Object) Sorting:** Sorting complex structures (e.g., student tuples `(Name, Age)`) strictly based on a specific attribute.
* **Binary Insertion Sort:** An optimized variant that uses **Binary Search** ($O(\log n)$ comparisons) to find the correct insertion index within the already sorted subarray.
* **K-Sorted (Nearly Sorted) Array:** Efficiently sorting an array where every element is at most $K$ places away from its target position.
* **Running Median of a Data Stream:** Utilizing insertion sort logic dynamically to maintain a sorted pipeline and compute the running median of incoming integers.

### 4. ⚡ Merge Sort (Advanced)
* **Divide & Conquer Approach:** A stable, recursive sorting algorithm that divides the array into halves, sorts them, and merges them back.
* **Time Complexity:** Guarantees $O(n \log n)$ performance across best, average, and worst-case scenarios.

---

## 💻 Tech Stack
* **Language:** Python 3
* **Environment:** Jupyter Notebook / Google Colab

---

## 🏃‍♂️ How to Run the Notebook

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git)
