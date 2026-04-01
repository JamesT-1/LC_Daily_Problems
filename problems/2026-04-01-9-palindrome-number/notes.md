9. Palindrome Number

Problem:
You’re given a number x
Palindrome means the number reads the same forward and backward
Check if reversing the number gives you the same number.

Solution:
Turn the number into a string, reverse it, and compare
Convert number to string
"121"
Reverse it
"121"[::-1] -> "121"
Compare
"121" == "121" -> True
