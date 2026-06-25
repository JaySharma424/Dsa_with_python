# 🚀 Array & String - DSA Problems (Python)

Welcome to the **Array & String** problem-solving repository! This repository contains a curated collection of fundamental Data Structures and Algorithms (DSA) questions implemented in Python. These problems focus on essential concepts like **Two-Pointers, Sliding Window, Frequency Counting, and In-Place Array Manipulations**.

---

## 📌 Table of Contents
1. [Sum of First and Last Element](#1-sum-of-first-and-last-element)
2. [Reverse a String (Without Built-ins)](#2-reverse-a-string-without-built-ins)
3. [Move Zeros to the End (In-Place)](#3-move-zeros-to-the-end-in-place)
4. [Valid Palindrome (With Alphanumeric Check)](#4-valid-palindrome-with-alphanumeric-check)
5. [Maximum Product of Two Distinct Elements](#5-maximum-product-of-two-distinct-elements)
6. [Reverse Each Word Individually](#6-reverse-each-word-individually)
7. [Character Frequency Counter](#7-character-frequency-counter)
8. [Second Largest Number in an Array](#8-second-largest-number-in-an-array)
9. [Remove Duplicates from Sorted Array](#9-remove-duplicates-from-sorted-array)
10. [Separate Positives and Negatives](#10-separate-positives-and-negatives)
11. [Valid Palindrome II (One Deletion Allowed)](#11-valid-palindrome-ii-one-deletion-allowed)
12. [Count Pairs Whose Sum is Less than Target](#12-count-pairs-whose-sum-is-less-than-target)
13. [Container With Most Water](#13-container-with-most-water)

---

## 💻 Problem Statements & Solutions

### 1. Sum of First and Last Element
* **Problem:** Take a list of integers and return the sum of the first and last elements. Handle edge cases for empty lists and single-element lists.
* **Complexity:** Time: $O(1)$ | Space: $O(1)$

### 2. Reverse a String (Without Built-ins)
* **Problem:** Reverse a given string without using Python's built-in `reversed()` function or extended slicing `[::-1]`.
* **Approach:** Iterating backwards from the end of the string.

### 3. Move Zeros to the End (In-Place)
* **Problem:** Move all zeros to the end of the array while maintaining the relative order of the non-zero elements.
* **Approach:** Two-pointer approach to swap non-zero elements forward.
* **Complexity:** Time: $O(N)$ | Space: $O(1)$

### 4. Valid Palindrome (With Alphanumeric Check)
* **Problem:** Check if a string is a palindrome, ignoring cases and non-alphanumeric characters.
* **Approach:** Two-pointer technique (`left` and `right`) meeting at the center.

### 5. Maximum Product of Two Distinct Elements
* **Problem:** Find the maximum product of two distinct elements in an array containing positive integers.
* **Approach:** Single pass ($O(N)$) tracking the two largest numbers (`max1` and `max2`).

### 6. Reverse Each Word Individually
* **Problem:** Reverse each word in a sentence without changing the original word order.
* **Example:** `"hello world"` ➡️ `"olleh dlrow"`

### 7. Character Frequency Counter
* **Problem:** Count and print the frequency of each character in a given string using a Hash Map (Dictionary).

### 8. Second Largest Number in an Array
* **Problem:** Find the second largest number in a list of integers in a single traversal.

### 9. Remove Duplicates from Sorted Array
* **Problem:** Remove duplicates in-place from a sorted array and return the updated array.
* **Approach:** Two-pointer technique to overwrite duplicate values.

### 10. Separate Positives and Negatives
* **Problem:** Move all negative numbers to the left side and positive numbers to the right side of the array in-place.
* **Approach:** Two-pointer partition algorithm.

### 11. Valid Palindrome II (One Deletion Allowed)
* **Problem:** Check if a string can become a palindrome after deleting at most one character.
* **Approach:** Standard palindrome check until a mismatch is found, then verify the remaining substrings.

### 12. Count Pairs Whose Sum is Less than Target
* **Problem:** Given a sorted array, count the number of pairs $(i, j)$ where $i < j$ and $nums[i] + nums[j] < \text{target}$.

### 13. Container With Most Water
* **Problem:** Find two vertical lines that form a container holding the maximum area of water.
* **Approach:** Two-pointer greedy approach shrinking the width from both ends.
* **Complexity:** Time: $O(N)$ | Space: $O(1)$

---

## 🛠️ How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/JaySharma424/Dsa_with_python.git](https://github.com/JaySharma424/Dsa_with_python.git)
   cd Dsa_with_python
