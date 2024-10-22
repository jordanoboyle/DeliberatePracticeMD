Two-Point Iteration Challenges:

1. Check if an array is a palindrome.
Description: Write a function that checks if an array is a palindrome using two-point iteration (i.e., comparing elements from both ends of the array).
Example: [1, 2, 3, 2, 1] returns true, [1, 2, 3, 4, 5] returns false.

2. Find pairs with a given sum.
Description: Write a function that finds all unique pairs in an array that sum up to a given number. Use two-point iteration to optimize the solution.
Example: For array [1, 2, 3, 4, 5] and sum 5, the function returns [[1, 4], [2, 3]].

3. Find the maximum product of two numbers.
Description: Write a function that finds the maximum product of two different numbers in an array using two-point iteration.
Example: For array [1, 2, 3, 4, 5], the function returns 20 (product of 4 and 5).

4. Find the closest pair to a target sum.
Description: Write a function that finds a pair of numbers in a sorted array whose sum is closest to a given target number using two-point iteration.
Example: For array [1, 3, 4, 7, 10] and target 15, the function returns [4, 10].

5. Remove duplicates in-place in a sorted array.
Description: Write a function that removes duplicates from a sorted array in-place and returns the new length of the array using two-point iteration.
Example: For array [1, 1, 2, 2, 3, 4, 4, 5], the function modifies the array to [1, 2, 3, 4, 5] and returns 5.


NEXT SET OF PROBLEMS

2. Find the Longest Palindromic Subarray
Description: Write a function that finds the longest palindromic subarray within a given array using two-point iteration. Compare elements from both ends of potential subarrays to identify the longest one.
Example:
For input [1, 2, 3, 2, 1, 5, 6], the longest palindromic subarray is [1, 2, 3, 2, 1].


3. Find the First Mismatch Between Two Arrays
Description: Write a function that compares two arrays element by element using two-point iteration (from both ends). The function should return the indices of the first mismatched pair of elements. If both arrays are identical when compared this way, return null.
Example:
For input arrays [1, 2, 3, 4] and [1, 2, 5, 4], the first mismatch occurs at index 2 (3 vs 5), so return 2.
For input [9, 8, 7] and [9, 8, 7], the arrays are identical, so return null.