# cf--notes
These are my codeforces notes.

1. Difficult Contest [https://codeforces.com/contest/2125/problem/A] #800
   The first approach is naturally swapping, but the real breakthrough of the problem is knowing that you can just place rather than swap as you have to derange and not arrange so you can just count the elements and arrange them in one particular way such that it is impossible to get the letter in the problematic order. Just get them in TNF order.

3. Recycling Center [https://codeforces.com/contest/2128/problem/A] #800

4. Submission is All You Need [https://codeforces.com/contest/2130/problem/A] #800

5. Deque Process [https://codeforces.com/contest/2128/problem/B] #1100

6. Forked! [https://codeforces.com/contest/1904/problem/A] #900

7. Vasilije in Cacak [https://codeforces.com/contest/1878/problem/C] #900

8. B. Swap and Delete [https://codeforces.com/problemset/problem/1913/B] #1000 #35mins
   This problem again reminds me of the two other problems that I have done one is of the good array and the other is of arranging, the first approach I thought just excess 1s or 0s will be the minimum number of coins but I quickly realised that the problem with this approach is that we can only delete from the resulting array not from the original therefore we have to replace the 1s and 0s with the other from left to right first and as soon as we can't everything else has to be deleted.

9. Replace with Occurrences [https://codeforces.com/contest/2137/problem/D] #1200 #54min

10. Fun Permutation [https://codeforces.com/contest/2137/problem/B] #900 #13min

11. Longest Divisors Interval [https://codeforces.com/contest/1855/problem/B] #900 #12mins
    insight : the insight of the problem was any consecutive numbers are going to be the multiples of the same number of first natural numbers, hence they will be the divisor of the ultimate number and hence the first natural numbers from 1 to n will be the maximum interval.
    This problem was again I cracked really quickly the insight, but I started thinking about the problem without looking at the testcases. Once I realised the problem's solution, again there was a longing for a proof and I made very minute mistakes in code, otherwise the problem could've been solved in under 5 minutes.

13. Assembly via Minimums [https://codeforces.com/contest/1857/problem/C] #1200 #45mins
    insight : the order does not matter && the maximum number would not appear in the b array, and you can't arbitrarily choose maximum because of the edge case that says all numbers should be in the limit including the maximum.
    I started coding up the problem, and it was pretty decent from the very beginning and I was also able to analyze the edge cases, and also I wasted some time going to the bathroom in b/w, so realistacally could have been done in 35 mins, which is really great.

14. Make It Zero [https://codeforces.com/contest/1869/problem/A] #900 #28mins
    insight : The whole problem was bloatware, a lot of information given just to make it sound complicated and contraints to make it look challenging, but the whole problem required 4 steps max for odd and 2 steps max for even size arrays, the numbers inside the array did not matter at all either, the problem got me lacking and I started trying to find weird results from bitwise XOR, but I only needed to know two results to solve the whole problem a xor a = 0 and a xor 0 = a, I might not even need the second result to be honest. Bitchasss problem took advantage of a vulnerable man.


15. Contrast Value [https://codeforces.com/contest/1832/problem/C] # 1200 #35 mins
    insight : the array can be reduced to peaks and valleys only.
I got the fucking insight real quick, but I wrote bad code that broke at multiple places without a proper algorithm in place, made for so much debugging, I should have first thought of all the edge cases as there were very few of them while writing a clean algorithm on the first try and submitted the right code, but finding the bug took a little trial and error which wasted so much time.

squarepoint challenge (cf round 1055, Div 1 + Div 2)

16. A. Increase or Smash [https://codeforces.com/contest/2152/problem/A]
    insight : there was realistically only one way to do it that was also progressing the problem closer to goal, prove.
17. B. Catching the Krug [https://codeforces.com/contest/2152/problem/B]
    insight : Very chess like, the only way to catch was to trap if it wasn't already catchable in 1 move, so the runner was to run somewhere with the most space, so it takes longer to catch, and once the runner is trapped he won't be able to increase distance b/w him and cahser, so the final result was distance + runway ahead. Look again to cement in head !
18. C. Triple Removal [https://codeforces.com/contest/2152/problem/C]
    insight : very easy to figure out the impossible case was where 1s or 0s count was not divisble by 3, only the alternate case was the one where there required an extra 1 cost for solving everywhere else it kind of figured itself out, prove.
