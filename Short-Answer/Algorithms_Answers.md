#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) - The number of times is based on the value of 'n'

b) O(n^2) - There are 2 checks of 'n' and thus would result in a n^2 complexity

c) O(n) - Recursion function. It is running linearly but reducing to zero

## Exercise II

Answer:

In order to figure out which floor the egg will not break we can start from the n-th or 1st floor and go linearly in order to verify where the egg breaks or does not break. This approach towards solving the problem isn't efficient, for example, what if the building is 100 floors? 

A better approach would be binary search. We can start the search half way and eliminate the unecessary half. 

middle = (highest_floor + lowest_floor) // 2

Assume it's a 20 story building and the middle floor is the 10th floor. Also assume that the egg breaks from the 10th floor, so we would test the lower floor that is the 9th floor and left side of the array. On the 9th floor the egg does not break, so we go to the 11th floor.

