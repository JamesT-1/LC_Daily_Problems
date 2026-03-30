2840. Check if Strings Can be Made Equal With Operations II

Problem:
You have two strings s1 and s2 of the same length. You can swap two letters in a string if:
The first letter is at index i, the second is at index j.
The distance between them (j - i) is even.
You can do this as many times as you want, on either string.

Solution:
We are making 4 arrays (lists) to separate letters:
even1 - letters from s1 at even positions (0,2,4…)
even2 - letters from s2 at even positions
odd1 - letters from s1 at odd positions (1,3,5…)
odd2 - letters from s2 at odd positions

Loop through every index i of the strings.
Push the letters into the right arrays
Sort the letters
Check if the letters match exactly
Compare sorted arrays
If even letters match and odd letters match, return true
Otherwise, return false
