# Leetcode_Day62
## Day 62 – LeetCode 2396: Strictly Palindromic Number

**Problem:** [Strictly Palindromic Number](https://leetcode.com/problems/strictly-palindromic-number/)  
**Difficulty:** Medium  
**Language:** Java  
**Topic:** Number Systems, Mathematical Observation

### Approach
- A number is strictly palindromic if its representation is a palindrome in every base from `2` to `n - 2`.
- Instead of converting the number into every possible base, we can use a mathematical observation.
- For every valid input `n >= 4`, the number is not strictly palindromic.
- Therefore, we can directly return `false`.

### Java Solution
```java
class Solution {
    public boolean isStrictlyPalindromic(int n) {
        return false;
    }
}

Complexity Analysis
- Time Complexity: O(1)
- Space Complexity: O(1)
Key Learning
Sometimes, the best solution is not to perform the operations described in the problem but to identify a mathematical property that eliminates the need for them.
Day 62/100 — Consistency over complexity! 🚀
#LeetCode #Java #DSA #ProblemSolving #100DaysOfCode
```
