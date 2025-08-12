# Binary Search — Problem Solutions

This folder contains solutions to problems that can be solved using **Binary Search** and its variations.

---

## 📌 Overview
Binary Search is an efficient algorithm for finding a target value in a **sorted array** (or search space) by repeatedly dividing the search interval in half.

---

## 🔍 Binary Search Algorithm Steps
1. Initialize `left` and `right` pointers to the start and end of the search space.
2. While `left <= right`:
   - Find the middle index `mid = (left + right) // 2`.
   - If `nums[mid]` equals the target → return the index.
   - If left half is sorted:
     - Check if the target lies in this range → move `right` to `mid - 1`.
     - Else → move `left` to `mid + 1`.
   - Else (right half is sorted):
     - Check if the target lies in this range → move `left` to `mid + 1`.
     - Else → move `right` to `mid - 1`.
3. If the target is not found → return `-1`.

---

## ⏱️ Complexity
- **Time Complexity:** O(log n)
- **Space Complexity:** O(1)

---

## 🧠 Variations of Binary Search Covered
- Standard Binary Search
- Search in Rotated Sorted Array
- First & Last Occurrence of Target
- Search in Infinite Sorted Array
- Search in 2D Matrix
- Peak Element Search
- Aggressive Cows / Allocate Minimum Pages (Binary Search on Answer)
- Median of Two Sorted Arrays

