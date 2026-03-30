1. Two Sum

Problem:
A list of numbers called nums
A target number the sum you want

You need two numbers in the list that add up to the target, and then return their positions (indices) in the array.

Solution:
First, pick a number (outer loop).
Then, check every number after it (inner loop) to see if they sum to the target.
If yes → return the indices.
