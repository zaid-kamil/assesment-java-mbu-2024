Practice questions in any order you like. Try to understand and solve the question, take help from various offline/online resources

## Problem : Best Time to Buy and Sell Stock
You are given an array `prices` where `prices[i]` is the price of a given stock on the `i-th` day. You want to maximize your profit by choosing a single day to buy one stock and choosing a different day in the future to sell that stock.

**Example:**
Input: `prices = [7, 1, 5, 3, 6, 4]`
Output: `5`

**Hint:** Keep track of the minimum price and the maximum profit.

[Link to LeetCode](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)

## Problem : Contains Duplicate
Given an array of integers, find if the array contains any duplicates. Your function should return `true` if any value appears at least twice in the array, and it should return `false` if every element is distinct.

**Example:**
Input: `nums = [1, 2, 3, 1]`
Output: `true`

**Hint:** Use a set to track the elements you have seen so far.

[Link to LeetCode](https://leetcode.com/problems/contains-duplicate/)

## Problem : Product of Array Except Self
Given an array `nums` of `n` integers where `n > 1`, return an array `output` such that `output[i]` is equal to the product of all the elements of `nums` except `nums[i]`.

**Example:**
Input: `nums = [1, 2, 3, 4]`
Output: `[24, 12, 8, 6]`

**Hint:** Use two arrays to store the product of all elements to the left and right of each element.

[Link to LeetCode](https://leetcode.com/problems/product-of-array-except-self/)

## Problem : Maximum Subarray
Given an integer array `nums`, find the contiguous subarray (containing at least one number) which has the largest sum and return its sum.

**Example:**
Input: `nums = [-2,1,-3,4,-1,2,1,-5,4]`
Output: `6`

**Hint:** Use Kadane's algorithm to solve this problem.

[Link to LeetCode](https://leetcode.com/problems/maximum-subarray/)

## Problem : Move Zeroes
Given an array `nums`, write a function to move all `0`s to the end of it while maintaining the relative order of the non-zero elements.

**Example:**
Input: `nums = [0, 1, 0, 3, 12]`
Output: `[1, 3, 12, 0, 0]`

**Hint:** Use two pointers to solve this problem.

[Link to LeetCode](https://leetcode.com/problems/move-zeroes/)

## Problem : Find All Numbers Disappeared in an Array
Given an array of integers where `1 ≤ a[i] ≤ n` (n = size of array), some elements appear twice and others appear once. Find all the elements of `[1, n]` inclusive that do not appear in this array.

**Example:**
Input: `nums = [4, 3, 2, 7, 8, 2, 3, 1]`
Output: `[5, 6]`

**Hint:** Use the array indices to mark the presence of numbers.

[Link to LeetCode](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/)

## Problem : Rotate Array
Given an array, rotate the array to the right by `k` steps, where `k` is non-negative.

**Example:**
Input: `nums = [1, 2, 3, 4, 5, 6, 7], k = 3`
Output: `[5, 6, 7, 1, 2, 3, 4]`

**Hint:** Use reverse operations to achieve the rotation.

[Link to LeetCode](https://leetcode.com/problems/rotate-array/)


## Problem : Third Maximum Number
Given a non-empty array of integers, return the third maximum number in this array. If it does not exist, return the maximum number.

**Example:**
Input: `nums = [3, 2, 1]`
Output: `1`

**Hint:** Use a set to keep track of the top three maximum numbers.

[Link to LeetCode](https://leetcode.com/problems/third-maximum-number/)

## Problem : Find the Duplicate Number
Given an array `nums` containing `n + 1` integers where each integer is between `1` and `n` (inclusive), prove that at least one duplicate number must exist. Assume that there is only one duplicate number, find the duplicate one.

**Example:**
Input: `nums = [1, 3, 4, 2, 2]`
Output: `2`

**Hint:** Use the Floyd's Tortoise and Hare (Cycle Detection) algorithm.

[Link to LeetCode](https://leetcode.com/problems/find-the-duplicate-number/)

## Problem : Merge Intervals
Given a collection of intervals, merge all overlapping intervals.

**Example:**
Input: `intervals = [[1, 3], [2, 6], [8, 10], [15, 18]]`
Output: `[[1, 6], [8, 10], [15, 18]]`

**Hint:** Sort the intervals by their start time.

[Link to LeetCode](https://leetcode.com/problems/merge-intervals/)


## Problem : Find Peak Element
A peak element is an element that is strictly greater than its neighbors. Given an input array `nums`, where `nums[i] ≠ nums[i+1]`, find a peak element and return its index.

**Example:**
Input: `nums = [1, 2, 3, 1]`
Output: `2`

**Hint:** Use binary search to find the peak element.

[Link to LeetCode](https://leetcode.com/problems/find-peak-element/)