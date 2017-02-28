# MasterMind

Points : 50

Solves : 90

## Question

Can you break my three digit lock?

+-----------------------+
|       |       |       |
|   7   |   3   |   6   | One number is correct but wrongly placed
|       |       |       |
|_______|_______|_______|
|       |       |       |
|   0   |   6   |   5   | One number is correct and correctly placed
|       |       |       |
|_______|_______|_______|
|       |       |       |
|   3   |   7   |   2   | Two numbers are correct but wrongly placed
|       |       |       |
|_______|_______|_______|
|       |       |       |
|   6   |   4   |   7   | No numbers are correct
|       |       |       |
|_______|_______|_______|
|       |       |       |
|   5   |   2   |   4   | One number is correct and correctly placed
|       |       |       |
|       |       |       |
+-----------------------+

## Solution

Initial set of possible numbers = {[0|1|2|3|4|5|6|7|8|9],[0|1|2|3|4|5|6|7|8|9],[0|1|2|3|4|5|6|7|8|9]}
From statement 4, the numbers 6, 4 and 7 are not in the solution... new set = {[0|1|2|3|5|8|9],[0|1|2|3|5|8|9],[0|1|2|3|5|8|9]}
From statement 3 we infer that 3 and 2 are in the solution but not in correct place... new set = {[0|1|2*|5|8|9],[0|1|2|3*|5|8|9],[0|1|3*|5|8|9]}
From statement 2, we see that 3 is only possible correct value but wrongly placed, so 3 goes at the end... new set = {[0|1|2*|5|8|9],[0|1|2*|5|8|9],[3*]}
From statement 5, only 2 that is for sure in the solution is also correctly placed... 5 is not in th solution set... new set = {[0|1|8|9],[2*],[3*]}
From statement 1, 0 is the last correctly placed number of the solution... solution set = {[0],[2],[3]}
