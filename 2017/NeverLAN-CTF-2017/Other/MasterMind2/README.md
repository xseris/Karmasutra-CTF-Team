# MasterMind

Points : 100

Solves : 82

## Question

I've upgraded my lock! Can you solve it?

+-------------------------------+
|       |       |       |       |
|   9   |   5   |   3   |   2   | One number is correct but wrongly placed
|       |       |       |       |
|_______|_______|_______|_______|
|       |       |       |       |
|   1   |   6   |   7   |   3   | Two numbers are correct and correctly placed
|       |       |       |       |
|_______|_______|_______|_______|
|       |       |       |       |
|   0   |   6   |   5   |   9   | Two numbers are correct but wrongly placed
|       |       |       |       |
|_______|_______|_______|_______|
|       |       |       |       |
|   2   |   4   |   3   |   8   | No numbers are correct
|       |       |       |       |
|_______|_______|_______|_______|
|       |       |       |       |
|   5   |   2   |   4   |   0   | One number is correct and correctly placed
|       |       |       |       |
|       |       |       |       |
+-------------------------------+

## Solution

Initial set of possible numbers = {[0|1|2|3|4|5|6|7|8|9],[0|1|2|3|4|5|6|7|8|9],[0|1|2|3|4|5|6|7|8|9],[0|1|2|3|4|5|6|7|8|9]}
From statement 4, the numbers 2, 3, 4 and 8 are not in the solution... new set = {[0|1|5|6|7|9],[0|1|5|6|7|9],[0|1|5|6|7|9],[0|1|5|6|7|9]}
...
1970
