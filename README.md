## leetcode Python_Programs.
### 1. (leetcode problem) 125. Valid Palindrome 
problem statement
A phrase is a palindrome if, after converting all uppercase letters into lowercase letters and removing all non-alphanumeric characters, it reads the same forward and backward. Alphanumeric characters include letters and numbers.
##### Solution1
use two pointers left and right.Time complexity O(n).Space complexity O(1) as no extra space is used.

### 2. (leetcode problem) 217. Contains Duplicate 
Problem satement
Given an integer array nums, return true if any value appears at least twice in the array, and return false if every element is distinct.
##### Solution1
use 2 for loops to compare every element in the list if they are same retun True
time complexity --> O(n^2)
##### Solution2
use a hash set to check 
time complexity --> O(n)
