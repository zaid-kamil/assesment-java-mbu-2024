# LeetCode Problems

This fike contains 20 LeetCode problems. 

## Problem List

1. **Two Sum** (LeetCode #1)
   - **Description**: Given an array of integers, find two numbers such that they add up to a specific target.
   - **Input**: `nums = [2, 7, 11, 15], target = 9`
   - **Output**: `[0, 1]`
   - **Hint**: Use a hash map to store each number's index as you iterate through the list.

2. **Palindrome Number** (LeetCode #9)
   - **Description**: Determine whether an integer is a palindrome.
   - **Input**: `x = 121`
   - **Output**: `true`
   - **Hint**: Convert the number to a string and check if it reads the same forwards and backwards.

3. **Roman to Integer** (LeetCode #13)
   - **Description**: Convert a Roman numeral to an integer.
   - **Input**: `s = "III"`
   - **Output**: `3`
   - **Hint**: Map each Roman numeral to its integer value, and handle special cases where smaller values precede larger ones.

4. **Valid Parentheses** (LeetCode #20)
   - **Description**: Check if the input string has valid parentheses.
   - **Input**: `s = "()[]{}"`
   - **Output**: `true`
   - **Hint**: Use a stack to match opening and closing parentheses.

5. **Merge Two Sorted Lists** (LeetCode #21)
   - **Description**: Merge two sorted linked lists into one sorted linked list.
   - **Input**: `l1 = [1, 2, 4], l2 = [1, 3, 4]`
   - **Output**: `[1, 1, 2, 3, 4, 4]`
   - **Hint**: Use two pointers to compare elements from each list and build a new sorted list.

6. **Remove Duplicates from Sorted Array** (LeetCode #26)
   - **Description**: Remove duplicates from a sorted array and return the new length.
   - **Input**: `nums = [1, 1, 2]`
   - **Output**: `2, nums = [1, 2, _]`
   - **Hint**: Use two pointers to overwrite duplicates.

7. **Remove Element** (LeetCode #27)
   - **Description**: Remove all instances of a specific value in an array and return the new length.
   - **Input**: `nums = [3, 2, 2, 3], val = 3`
   - **Output**: `2, nums = [2, 2, _, _]`
   - **Hint**: Use two pointers; one to traverse and one to overwrite unwanted values.

8. **Implement strStr()** (LeetCode #28)
   - **Description**: Return the index of the first occurrence of a substring in a string.
   - **Input**: `haystack = "hello", needle = "ll"`
   - **Output**: `2`
   - **Hint**: Use the sliding window technique or check string methods.

9. **Search Insert Position** (LeetCode #35)
   - **Description**: Given a sorted array and a target, find the index where the target would fit.
   - **Input**: `nums = [1, 3, 5, 6], target = 5`
   - **Output**: `2`
   - **Hint**: Use binary search for efficiency.

10. **Maximum Subarray** (LeetCode #53)
    - **Description**: Find the contiguous subarray with the largest sum.
    - **Input**: `nums = [-2,1,-3,4,-1,2,1,-5,4]`
    - **Output**: `6`
    - **Hint**: Use Kadane's Algorithm to keep track of maximum subarray sums.

11. **Length of Last Word** (LeetCode #58)
    - **Description**: Return the length of the last word in a string.
    - **Input**: `s = "Hello World"`
    - **Output**: `5`
    - **Hint**: Split the string by spaces and return the last non-empty word.

12. **Plus One** (LeetCode #66)
    - **Description**: Given an array of digits, increment the integer by one.
    - **Input**: `digits = [1, 2, 3]`
    - **Output**: `[1, 2, 4]`
    - **Hint**: Handle carry-over if the last digit is 9.

13. **Add Binary** (LeetCode #67)
    - **Description**: Add two binary numbers represented as strings.
    - **Input**: `a = "11", b = "1"`
    - **Output**: `"100"`
    - **Hint**: Start from the end of each string and add digits with carry.

14. **Sqrt(x)** (LeetCode #69)
    - **Description**: Compute and return the square root of a non-negative integer.
    - **Input**: `x = 8`
    - **Output**: `2`
    - **Hint**: Use binary search or the Newton-Raphson method.

15. **Climbing Stairs** (LeetCode #70)
    - **Description**: Find the number of distinct ways to reach the top of a staircase.
    - **Input**: `n = 3`
    - **Output**: `3`
    - **Hint**: This is a Fibonacci sequence problem.

16. **Remove Linked List Elements** (LeetCode #203)
    - **Description**: Remove all elements from a linked list that have a specific value.
    - **Input**: `head = [1, 2, 6, 3, 4, 5, 6], val = 6`
    - **Output**: `[1, 2, 3, 4, 5]`
    - **Hint**: Use a dummy node to simplify deletion of nodes.

17. **Reverse Linked List** (LeetCode #206)
    - **Description**: Reverse a singly linked list.
    - **Input**: `head = [1, 2, 3, 4, 5]`
    - **Output**: `[5, 4, 3, 2, 1]`
    - **Hint**: Use iterative or recursive methods to reverse pointers.

18. **Best Time to Buy and Sell Stock** (LeetCode #121)
    - **Description**: Find the maximum profit from buying and selling a stock once.
    - **Input**: `prices = [7, 1, 5, 3, 6, 4]`
    - **Output**: `5`
    - **Hint**: Track the minimum price encountered and calculate potential profit.

19. **Intersection of Two Linked Lists** (LeetCode #160)
    - **Description**: Find the node where two linked lists intersect.
    - **Input**: `headA = [4, 1, 8, 4, 5], headB = [5, 6, 1, 8, 4, 5]`
    - **Output**: `Reference of node with value 8`
    - **Hint**: Use two pointers and switch lists when one reaches the end.

20. **Binary Tree Inorder Traversal** (LeetCode #94)
    - **Description**: Perform an inorder traversal on a binary tree.
    - **Input**: `root = [1, null, 2, 3]`
    - **Output**: `[1, 3, 2]`
    - **Hint**: Use recursion or a stack to simulate inorder traversal.
