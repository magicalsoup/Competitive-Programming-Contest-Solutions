Because the input data are small, brute force will suffice. Find all pairs of factors by trial division, 
and then for every pair of pairs, determine whether the sum of one pair equals the difference of the other. 
The number of factors of a number N is approximately bounded above by log N, so the slowest step is determining the 
factors in the first place. Thus, efficiency is not an issue with N ≤ 32000. See bbi5291's solution for implementation details.

Or you can use some magic
find the numbers that are divisible by 6!
