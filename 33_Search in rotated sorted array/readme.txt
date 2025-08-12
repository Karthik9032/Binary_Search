Problem Title & Brief Summary
Search in Rotated Sorted Array — Given a rotated sorted array, find the target value’s index in O(log n) time, or return -1 if absent 
Medium
WalkCCC
.

Approach Explanation
We use a modified binary search to account for rotation: detect which half (left or right) is sorted, then check if the target is within that range and narrow the search accordingly 
AlgoMonster
WalkCCC
.

Time & Space Complexity

Time: O(log n)

Space: O(1)