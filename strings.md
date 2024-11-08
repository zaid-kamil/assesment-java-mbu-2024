## Problem 1: Reverse String
Write a function that reverses a string. The input string is given as an array of characters `s`.

**Example:**
Input: `s = ["h","e","l","l","o"]`
Output: `["o","l","l","e","h"]`

**Hint:** Use two pointers to swap characters from both ends of the string.

[Link to LeetCode](https://leetcode.com/problems/reverse-string/)

## Problem 2: Valid Anagram
Given two strings `s` and `t`, return `true` if `t` is an anagram of `s`, and `false` otherwise.

**Example:**
Input: `s = "anagram", t = "nagaram"`
Output: `true`

**Hint:** Use a hash map to count the occurrences of each character.

[Link to LeetCode](https://leetcode.com/problems/valid-anagram/)

## Problem 3: First Unique Character in a String
Given a string `s`, find the first non-repeating character in it and return its index. If it does not exist, return `-1`.

**Example:**
Input: `s = "leetcode"`
Output: `0`

**Hint:** Use a hash map to count the occurrences of each character.

[Link to LeetCode](https://leetcode.com/problems/first-unique-character-in-a-string/)

## Problem 4: Implement strStr()
Return the index of the first occurrence of needle in haystack, or `-1` if needle is not part of haystack.

**Example:**
Input: `haystack = "hello", needle = "ll"`
Output: `2`

**Hint:** Use the sliding window technique to check for the substring.

[Link to LeetCode](https://leetcode.com/problems/implement-strstr/)

## Problem 5: Longest Common Prefix
Write a function to find the longest common prefix string amongst an array of strings. If there is no common prefix, return an empty string `""`.

**Example:**
Input: `strs = ["flower","flow","flight"]`
Output: `"fl"`

**Hint:** Compare characters of each string one by one.

[Link to LeetCode](https://leetcode.com/problems/longest-common-prefix/)

## Problem 6: Palindrome Check
Given a string `s`, determine if it is a palindrome, considering only alphanumeric characters and ignoring cases.

**Example:**
Input: `s = "A man, a plan, a canal: Panama"`
Output: `true`

**Hint:** Use two pointers to compare characters from both ends of the string.

[Link to LeetCode](https://leetcode.com/problems/valid-palindrome/)

## Problem 7: Count and Say
The count-and-say sequence is a sequence of digit strings defined by the recursive formula:
- `countAndSay(1) = "1"`
- `countAndSay(n)` is the way you would "say" the digit string from `countAndSay(n-1)`, which is then converted into a different digit string.

**Example:**
Input: `n = 4`
Output: `"1211"`

**Hint:** Use a loop to generate the sequence iteratively.

[Link to LeetCode](https://leetcode.com/problems/count-and-say/)

## Problem 8: Longest Substring Without Repeating Characters
Given a string `s`, find the length of the longest substring without repeating characters.

**Example:**
Input: `s = "abcabcbb"`
Output: `3`

**Hint:** Use a sliding window approach with a set to track characters.

[Link to LeetCode](https://leetcode.com/problems/longest-substring-without-repeating-characters/)

## Problem 9: String to Integer (atoi)
Implement the `myAtoi(string s)` function, which converts a string to a 32-bit signed integer.

**Example:**
Input: `s = "42"`
Output: `42`

**Hint:** Handle leading whitespaces, optional sign, and overflow conditions.

[Link to LeetCode](https://leetcode.com/problems/string-to-integer-atoi/)

## Problem 10: Group Anagrams
Given an array of strings `strs`, group the anagrams together. You can return the answer in any order.

**Example:**
Input: `strs = ["eat","tea","tan","ate","nat","bat"]`
Output: `[["eat","tea","ate"],["tan","nat"],["bat"]]`

**Hint:** Use a hash map to group strings by their sorted characters.

[Link to LeetCode](https://leetcode.com/problems/group-anagrams/)

## Problem 11: Longest Palindromic Substring
Given a string `s`, return the longest palindromic substring in `s`.

**Example:**
Input: `s = "babad"`
Output: `"bab"` or `"aba"`

**Hint:** Use expand around center approach.

[Link to LeetCode](https://leetcode.com/problems/longest-palindromic-substring/)

## Problem 12: Valid Parentheses
Given a string `s` containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.

**Example:**
Input: `s = "()[]{}"`
Output: `true`

**Hint:** Use a stack to keep track of opening brackets.

[Link to LeetCode](https://leetcode.com/problems/valid-parentheses/)

## Problem 13: Roman to Integer
Given a roman numeral, convert it to an integer.

**Example:**
Input: `s = "III"`
Output: `3`

**Hint:** Use a hash map to store roman numeral values and iterate through the string.

[Link to LeetCode](https://leetcode.com/problems/roman-to-integer/)

## Problem 14: Integer to Roman
Given an integer, convert it to a roman numeral.

**Example:**
Input: `num = 58`
Output: `"LVIII"`

**Hint:** Use arrays to store roman numeral values and corresponding symbols.

[Link to LeetCode](https://leetcode.com/problems/integer-to-roman/)

## Problem 15: Longest Common Subsequence
Given two strings `text1` and `text2`, return the length of their longest common subsequence.

**Example:**
Input: `text1 = "abcde", text2 = "ace"`
Output: `3`

**Hint:** Use dynamic programming with a 2D array.

[Link to LeetCode](https://leetcode.com/problems/longest-common-subsequence/)

## Problem 16: Check If a String Is a Valid Sequence from Root to Leaves Path in a Binary Tree
Given a binary tree where each node contains a value from 0 to 9, and a string `s`, determine if the string is a valid sequence from root to leaves path in the binary tree.

**Example:**
Input: `root = [0,1,0,0,1,0,null,null,1,0,0], s = "011"`
Output: `true`

**Hint:** Use depth-first search (DFS) to traverse the tree.

[Link to LeetCode](https://leetcode.com/problems/check-if-a-string-is-a-valid-sequence-from-root-to-leaves-path-in-a-binary-tree/)

## Problem 17: Add Binary
Given two binary strings `a` and `b`, return their sum as a binary string.

**Example:**
Input: `a = "11", b = "1"`
Output: `"100"`

**Hint:** Use bit manipulation or simulate binary addition.

[Link to LeetCode](https://leetcode.com/problems/add-binary/)

## Problem 18: Multiply Strings
Given two non-negative integers `num1` and `num2` represented as strings, return the product of `num1` and `num2`, also represented as a string.

**Example:**
Input: `num1 = "2", num2 = "3"`
Output: `"6"`

**Hint:** Use elementary school multiplication method.

[Link to LeetCode](https://leetcode.com/problems/multiply-strings/)

## Problem 19: Valid Palindrome II
Given a string `s`, return `true` if the `s` can be palindrome after deleting at most one character from it.

**Example:**
Input: `s = "abca"`
Output: `true`

**Hint:** Use two pointers to check for palindrome with one character removal.

[Link to LeetCode](https://leetcode.com/problems/valid-palindrome-ii/)

## Problem 20: Repeated Substring Pattern
Given a string `s`, check if it can be constructed by taking a substring of it and appending multiple copies of the substring together.

**Example:**
Input: `s = "abab"`
Output: `true`

**Hint:** Check if the string is a repeated pattern of its substring.

[Link to LeetCode](https://leetcode.com/problems/repeated-substring-pattern/)

## Problem 21: Find the Difference
You are given two strings `s` and `t`. String `t` is generated by random shuffling string `s` and then adding one more letter at a random position. Return the letter that was added to `t`.

**Example:**
Input: `s = "abcd", t = "abcde"`
Output: `"e"`

**Hint:** Use XOR to find the added character.

[Link to LeetCode](https://leetcode.com/problems/find-the-difference/)

## Problem 22: Longest Palindrome
Given a string `s` which consists of lowercase or uppercase letters, return the length of the longest palindrome that can be built with those letters.

**Example:**
Input: `s = "abccccdd"`
Output: `7`

**Hint:** Use a hash map to count character frequencies.

[Link to LeetCode](https://leetcode.com/problems/longest-palindrome/)

## Problem 23: Reverse Words in a String
Given an input string `s`, reverse the order of the words.

**Example:**
Input: `s = "the sky is blue"`
Output: `"blue is sky the"`

**Hint:** Split the string by spaces and reverse the list of words.

[Link to LeetCode](https://leetcode.com/problems/reverse-words-in-a-string/)

## Problem 24: Reverse Words in a String III
Given a string `s`, reverse the order of characters in each word within a sentence while still preserving whitespace and initial word order.

**Example:**
Input: `s = "Let's take LeetCode contest"`
Output: `"s'teL ekat edoCteeL tsetnoc"`

**Hint:** Split the string by spaces and reverse each word.

[Link to LeetCode](https://leetcode.com/problems/reverse-words-in-a-string-iii/)

## Problem 25: Valid Palindrome III
Given a string `s` and an integer `k`, return `true` if `s` is a k-palindrome.

**Example:**
Input: `s = "abcdeca", k = 2`
Output: `true`

**Hint:** Use dynamic programming to find the longest palindromic subsequence.

[Link to LeetCode](https://leetcode.com/problems/valid-palindrome-iii/)

## Problem 26: Longest Substring with At Least K Repeating Characters
Given a string `s` and an integer `k`, return the length of the longest substring of `s` such that the frequency of each character in this substring is at least `k`.

**Example:**
Input: `s = "aaabb", k = 3`
Output: `3`

**Hint:** Use divide and conquer approach.

[Link to LeetCode](https://leetcode.com/problems/longest-substring-with-at-least-k-repeating-characters/)

## Problem 27: Longest Substring with At Most Two Distinct Characters
Given a string `s`, return the length of the longest substring that contains at most two distinct characters.

**Example:**
Input: `s = "eceba"`
Output: `3`

**Hint:** Use sliding window approach with a hash map.

[Link to LeetCode](https://leetcode.com/problems/longest-substring-with-at-most-two-distinct-characters/)

## Problem 28: Longest Substring with At Most K Distinct Characters
Given a string `s` and an integer `k`, return the length of the longest substring that contains at most `k` distinct characters.

**Example:**
Input: `s = "eceba", k = 2`
Output: `3`

**Hint:** Use sliding window approach with a hash map.

[Link to LeetCode](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/)

## Problem 29: Minimum Window Substring
Given two strings `s` and `t`, return the minimum window in `s` which will contain all the characters in `t`.

**Example:**
Input: `s = "ADOBECODEBANC", t = "ABC"`
Output: `"BANC"`

**Hint:** Use sliding window approach with a hash map.

[Link to LeetCode](https://leetcode.com/problems/minimum-window-substring/)

## Problem 30: Decode String
Given an encoded string, return its decoded string.

**Example:**
Input: `s = "3[a]2[bc]"`
Output: `"aaabcbc"`

**Hint:** Use a stack to decode the string.

[Link to LeetCode](https://leetcode.com/problems/decode-string/)