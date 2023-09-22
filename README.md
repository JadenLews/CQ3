# CQ3
For mini max sum the code loops through all n values to find sum and then loops through them again to find max and min, the runtime is O(n)
the space complexity is O(1) because i have int max, int min, and int sum which is the same for all input

for my iteration method of hackerrank the method loops through all characters in string, and for each character does a check which makes the runtime O(N) the space complexity is O(1) because all that is saved is "hackerrank" and an int pointer

for the recursive version what happens is we iterate through string s until we find a character that doesn't line up with "hackerrank" the worst case scenero is when none of the characters line up with hackerrank and you keep recursivey searching but deleting the first letter each time, which would make it a run time of O(N) it is similar to iteration but what happens is the program makes a new string but with one of the non lining up characters gone, so the string gets 1 smaller each time. This means the runtime has to be O(n) because it does constant work in each recursion

The bottom image is mini max, the middle one is hackerrank with iteration, and the top is hackerrank with recursion
