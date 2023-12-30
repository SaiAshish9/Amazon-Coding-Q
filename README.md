# Amazon-Coding-Q

#Q1

```
general is finding the number of outcomes where his soldiers will win the
war given the number of days the war will go on. 
The possible number of wins given by d days = number of pure number sequences
of length d.

A pure number sequence is a sequence of digits where any digit (0-9) can come 
at any index i iff either n is 0(zero) or any divisor of n(except for 1) has
 been already placed before such that (j<i).

Guess the number of wins that General gets. Return the numbers of wins in
modulo 1e9+7
Input d = 1, answer = 9 (1,2,3,4,5,6,7,8,9)
d = 2, answer = 23 (1 to 9,20,22,24,26,28, 30,33, 36... and so on)
```
