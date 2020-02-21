# Beginning challenge
#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)  O(n) - Linear algorithm, runtime grows directly in proportion to n.  Dividing runtime of while loop (n^3) by runtime of inner (n^2) would give us O(n).


b)  O(n^2) - Sorting algorithm, the while statement is nested inside the for loop.  Outer loop running (n) times and the value of j is doubling during each iteration.


c)  O(n) - Recursive algorithm, the recursion is depent on (n) and will run until all iterations of "bunnies" have finished.

## Exercise II

O(n) runtime complexity -
<!-- 2 parameters - Egg and Floor_#
write a for loop that returns true or false depending on what floor the egg is dropped from
if floor is >= floor_f, return true (break)
otherwise, return false (didn't break) -->

List of length (n) for number of floors
Find center of floor #'s and divide bottom and top halves
Test for egg breaking at halfway point
If the egg breaks, repeat using lowest half of floor #'s
If the egg doesn't break, repeat using highest half of floor #'s
When down to final 2 floors, the floor where it breaks will point to the floor where it will not break
