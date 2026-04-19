13. Roman to Integer

Problem:
You’re given something like: "MCMXCIV"
This is a number written in Roman numerals, and your job is:
Turn it into a normal number (integer)
Normally you add numbers: VI = 5 + 1 = 6
But sometimes you subtract: IV = 5 - 1 = 4
If a smaller number comes before a bigger number subtract it
IV = 4 (1 before 5 → subtract)
IX = 9 (1 before 10 → subtract)
XL = 40 (10 before 50 → subtract)

Solution:
Start from the left side of the Roman number
Look at one letter at a time
For each letter: Compare it with the next letter
If the current letter is smaller than the next one subtract it
Otherwise add it
