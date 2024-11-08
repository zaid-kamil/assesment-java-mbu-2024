# CoCubes Coding Questions
## 1. **Prime Number Check**
**Description**: Write a program to check if a given number is a prime number. A prime number is one that is divisible only by 1 and itself.  
**Year**: 2022  

**Hints**:  
- Java: Use a loop from 2 to `sqrt(n)`. Check if the number has any divisor other than 1 and itself.
- Python: Use a similar loop and check divisibility. You may use `math.sqrt()` for optimization.
- JavaScript: Use a loop and check divisibility. The `Math.sqrt()` function can help improve performance.

---

## 2. **Palindrome String Check**
**Description**: Determine if a given string is a palindrome. A palindrome reads the same backward as forward.  
**Year**: 2021  

**Hints**:  
- Java: Use two-pointer technique to compare characters from the start and end of the string.
- Python: Reverse the string and compare it to the original.
- JavaScript: Convert the string to an array, reverse it, and join back to check equality.

---

## 3. **Fibonacci Sequence Generation**
**Description**: Generate the first `n` numbers in the Fibonacci sequence. The sequence starts with 0 and 1, and each subsequent number is the sum of the previous two.  
**Year**: 2023  

**Hints**:  
- Java: Use a loop to generate numbers, storing the previous two numbers to calculate the next.
- Python: Use a `for` loop or a recursive function.
- JavaScript: Use an array to store numbers as they are generated.

---

## 4. **Factorial Calculation**
**Description**: Write a program to calculate the factorial of a given number `n`. Factorial of `n` is the product of all positive integers up to `n`.  
**Year**: 2020  

**Hints**:  
- Java: Use recursion or a loop to multiply numbers from `1` to `n`.
- Python: Use recursion or the `math.factorial()` function.
- JavaScript: Use a loop or recursion for the multiplication process.

---

## 5. **Reverse an Array**
**Description**: Given an array of integers, reverse the elements of the array in place.  
**Year**: 2022  

**Hints**:  
- Java: Use two pointers from start and end, swapping elements.
- Python: Use slicing to reverse, or a loop with two pointers.
- JavaScript: Use the built-in `.reverse()` method or two-pointer approach.

---

## 6. **Find Missing Number in Array**
**Description**: In an array of `n` consecutive integers from 1 to `n+1`, find the missing number.  
**Year**: 2023  

**Hints**:  
- Java: Use the sum formula `n*(n+1)/2` and subtract the array’s sum.
- Python: Same approach as Java, using `sum()` function.
- JavaScript: Calculate total and subtract sum of elements in the array.

---

## 7. **Sum of Digits of a Number**
**Description**: Write a program to calculate the sum of the digits of a given number.  
**Year**: 2021  

**Hints**:  
- Java: Use a loop to get each digit using modulus and division.
- Python: Use a loop, or convert to string and sum digits.
- JavaScript: Use a loop or convert the number to a string and sum digits.

---

## 8. **Count Vowels in a String**
**Description**: Given a string, count the number of vowels (a, e, i, o, u) in the string.  
**Year**: 2020  

**Hints**:  
- Java: Use a loop and `if` statements to check each character.
- Python: Use a loop or list comprehension with conditionals.
- JavaScript: Use a loop or regular expression to count vowels.

---

## 9. **Check Armstrong Number**
**Description**: Determine if a given number is an Armstrong number. An Armstrong number for a given number of digits is a number that is equal to the sum of its digits each raised to the power of the number of digits.  
**Year**: 2022  

**Hints**:  
- Java: Calculate the power of each digit and sum it.
- Python: Use `**` operator for exponentiation of each digit.
- JavaScript: Use `Math.pow()` or `**` to compute each digit’s power.

---

## 10. **Find GCD of Two Numbers**
**Description**: Write a program to find the greatest common divisor (GCD) of two given integers.  
**Year**: 2023  

**Hints**:  
- Java: Use Euclidean algorithm with recursive or iterative approach.
- Python: Use recursion, or `math.gcd()` for simplicity.
- JavaScript: Use a loop or recursive method to implement the Euclidean algorithm.



## Intermediate level

## 1. **Count Distinct Elements in a Window**
**Description**: Given an array of integers and a number `k`, count the distinct elements in every window of size `k`.  
**Year**: 2021  

**Input Examples**:
- Input: `[1, 2, 1, 3, 4, 2, 3]`, `k = 4`  
  Output: `[3, 4, 4, 3]`
- Input: `[1, 2, 4, 4]`, `k = 2`  
  Output: `[2, 2, 1]`

---

## 2. **Sort Characters by Frequency**
**Description**: Given a string, sort it in decreasing order based on the frequency of characters.  
**Year**: 2020  

**Input Examples**:
- Input: `"tree"`  
  Output: `"eert"` or `"rtee"`
- Input: `"cccaaa"`  
  Output: `"cccaaa"`

---

## 3. **Reverse Words in a String**
**Description**: Given an input string, reverse the words without reversing the individual characters.  
**Year**: 2019  

**Input Examples**:
- Input: `"the sky is blue"`  
  Output: `"blue is sky the"`
- Input: `"hello world"`  
  Output: `"world hello"`

---

## 4. **Move Zeros to End**
**Description**: Write a program to move all 0's to the end of an array while maintaining the relative order of the non-zero elements.  
**Year**: 2022  

**Input Examples**:
- Input: `[0, 1, 0, 3, 12]`  
  Output: `[1, 3, 12, 0, 0]`
- Input: `[0, 0, 1]`  
  Output: `[1, 0, 0]`

---

## 5. **Intersection of Two Arrays**
**Description**: Given two arrays, return an array that represents their intersection. Each element in the result must appear as many times as it shows in both arrays.  
**Year**: 2021  

**Input Examples**:
- Input: `[1, 2, 2, 1]`, `[2, 2]`  
  Output: `[2, 2]`
- Input: `[4, 9, 5]`, `[9, 4, 9, 8, 4]`  
  Output: `[4, 9]`

---

## 6. **Find Majority Element**
**Description**: Find the element that appears more than `n/2` times in an array.  
**Year**: 2020  

**Input Examples**:
- Input: `[3, 2, 3]`  
  Output: `3`
- Input: `[2, 2, 1, 1, 1, 2, 2]`  
  Output: `2`

---

## 7. **First Unique Character in a String**
**Description**: Given a string, find the first non-repeating character and return its index. If it doesn’t exist, return -1.  
**Year**: 2019  

**Input Examples**:
- Input: `"leetcode"`  
  Output: `0`
- Input: `"loveleetcode"`  
  Output: `2`

---

## 8. **Find Pair with Given Sum**
**Description**: Given an array of integers and a target sum, find the indices of the two numbers that add up to the target sum.  
**Year**: 2022  

**Input Examples**:
- Input: `[2, 7, 11, 15]`, `target = 9`  
  Output: `[0, 1]`
- Input: `[3, 2, 4]`, `target = 6`  
  Output: `[1, 2]`

---

## 9. **Valid Anagram**
**Description**: Given two strings, determine if they are anagrams of each other.  
**Year**: 2021  

**Input Examples**:
- Input: `"anagram"`, `"nagaram"`  
  Output: `True`
- Input: `"rat"`, `"car"`  
  Output: `False`

---

## 10. **Find the Missing Number**
**Description**: Given an array containing `n` distinct numbers in the range `[0, n]`, find the missing number.  
**Year**: 2022  

**Input Examples**:
- Input: `[3, 0, 1]`  
  Output: `2`
- Input: `[0, 1]`  
  Output: `2`

## Advanced level 

## 1. **Subarray with Maximum Sum**
**Description**: Find the subarray within an array of integers that has the largest sum.

**Input Examples**:
- Input: `[-2, 1, -3, 4, -1, 2, 1, -5, 4]`  
  Output: `6`  (subarray `[4, -1, 2, 1]`)
- Input: `[1, 2, 3, -2, 5]`  
  Output: `9`  (subarray `[1, 2, 3, -2, 5]`)

---

## 2. **Longest Common Subsequence**
**Description**: Given two strings, find the length of their longest common subsequence.

**Input Examples**:
- Input: `"abcde"`, `"ace"`  
  Output: `3`  (subsequence `"ace"`)
- Input: `"abc"`, `"abc"`  
  Output: `3`  (subsequence `"abc"`)

---

## 3. **Minimum Edit Distance**
**Description**: Find the minimum number of operations (insert, delete, replace) required to convert one string into another.

**Input Examples**:
- Input: `"horse"`, `"ros"`  
  Output: `3`
- Input: `"intention"`, `"execution"`  
  Output: `5`

---

## 4. **K-th Largest Element in Array**
**Description**: Find the k-th largest element in an unsorted array.

**Input Examples**:
- Input: `[3, 2, 1, 5, 6, 4]`, `k=2`  
  Output: `5`
- Input: `[7, 10, 4, 3, 20, 15]`, `k=4`  
  Output: `7`

---

## 5. **Find All Permutations of a String**
**Description**: Generate all permutations of a given string.

**Input Examples**:
- Input: `"abc"`  
  Output: `["abc", "acb", "bac", "bca", "cab", "cba"]`
- Input: `"ab"`  
  Output: `["ab", "ba"]`

---

## 6. **Container With Most Water**
**Description**: Given an array where each element represents the height of a container’s side, find two lines that form a container with the most water.

**Input Examples**:
- Input: `[1, 8, 6, 2, 5, 4, 8, 3, 7]`  
  Output: `49`
- Input: `[1, 1]`  
  Output: `1`

---

## 7. **Longest Palindromic Substring**
**Description**: Given a string, find the longest substring that is a palindrome.

**Input Examples**:
- Input: `"babad"`  
  Output: `"bab"` or `"aba"`
- Input: `"cbbd"`  
  Output: `"bb"`

---

## 8. **Subset Sum Problem**
**Description**: Determine if there is a subset of the given array with a sum equal to a given sum.

**Input Examples**:
- Input: `[3, 34, 4, 12, 5, 2]`, `sum=9`  
  Output: `True`
- Input: `[1, 2, 3, 7]`, `sum=6`  
  Output: `True`

---

## 9. **Trapping Rain Water**
**Description**: Given an array representing heights, compute how much water can be trapped after raining.

**Input Examples**:
- Input: `[0,1,0,2,1,0,1,3,2,1,2,1]`  
  Output: `6`
- Input: `[4,2,0,3,2,5]`  
  Output: `9`

---

## 10. **Binary Tree Level Order Traversal**
**Description**: Given the root of a binary tree, return its level order traversal (from left to right, level by level).

**Input Examples**:
- Input: `root = [3,9,20,null,null,15,7]`  
  Output: `[[3], [9,20], [15,7]]`
- Input: `root = [1]`  
  Output: `[[1]]`

---
