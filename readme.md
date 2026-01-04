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

16. A. Increase or Smash [https://codeforces.com/contest/2152/problem/A] #800 #33mins  
    insight : there was realistically only one way to do it that was also progressing the problem closer to goal, prove.  
17. B. Catching the Krug [https://codeforces.com/contest/2152/problem/B] #1300 #27mins  
    insight : Very chess like, the only way to catch was to trap if it wasn't already catchable in 1 move, so the runner was to run somewhere with the most space, so it takes longer to catch, and once the runner is trapped he won't be able to increase distance b/w him and cahser, so the final result was distance + runway ahead. Look again to cement in head !  
18. C. Triple Removal [https://codeforces.com/contest/2152/problem/C] #1400 #60mins  
    insight : very easy to figure out the impossible case was where 1s or 0s count was not divisble by 3, only the alternate case was the one where there required an extra 1 cost for solving everywhere else it kind of figured itself out, prove.  

19. A. Cover in Water [https://codeforces.com/contest/1900/problem/A] #800 #16mins  
    insight : Infinite water is you have 3 consecutive spaces  
20. C. Ski Resort [https://codeforces.com/contest/1840/problem/C] #1000 #14mins  
    insight : None  
    Sliding Window template implementation, very easy  
21. E. Scuza [https://codeforces.com/contest/1742/problem/E] #1200 #43mins  
    insight : Monotonic Array reduction, sorting is not required  
    Simple Binary Search problem, but I fucked it because I did not know it's template so I wrote really stupid and repetitive code which took a long time. Also once I cracked the problem but realised that I have to write messy code, perfectionism came in and manifested itself in disinterest and boredom.  
22. E. Anna and the Valentine's Day Gift [https://codeforces.com/contest/1931/problem/E] #1400 #47mins  
    insight : The number of digits cannot be more than initial because of concatenation and trailing zeroes can be deleted by the opponent, and it will try to delete the most in one move, therefore once the deletable zeroes are sorted in the descending order the opponent will destroy all alternate deletable zeros while the protector will protect the inbetween ones.  
    Fucked it again, because I lacked focus at the end of the 2 hour thing and did not realise that sort() was sorting in ascending order and lost my head, trying to figure out what was going on. definitely wasted 20 mins doing that. could have solved in 27 mins.  

23. A. Operations with Inversions [https://codeforces.com/contest/2176/problem/A] #24mins  
    problem(What it looks like) : You need to delete elements of the array using a rule and the rule is such that it depends on the elements present in the array itself. This makes it look like a problem where we need to delete elements optimally / carefully to delete the most.
    reduction (insight) : the rule only looks like it depends on the present elements of the array but it really does not because if you delete some element using the rule you can still delete all the other elements that you could have deleted by applying the rule on the element that was just deleted.  
    
24. B. Optimal Shifts [https://codeforces.com/contest/2176/problem/B] #20mins
    problem(What it looks like) : You need to perform operations in a way to reach the goal and minimize the operation cost. You can either do incremental operations or variable jump operations you have to find the best combination of operations the criteria for best being the lowest cost and reaching the goal.
    reduction(insight) : The state cost of doing operations is linear meaning that doing an n jump operation cost the same as doing n incremental operations and at the same time doing incremental operations gaurantees reaching goals while doing jump operations does not. Therefore there is no issue of cost optimization and goal achievement is also gauranteed by doing incremental steps always.
    
26. C. C. Odd Process [https://codeforces.com/contest/2176/problem/C] #90mins
    problem(What it looks like) : You want to accumulate the maximum points but if a certain condition is reached you will loose all points and will have to start from zero. You have to accumulate points one by one in K turns.
    reduction(insight) : It is simply unavoidable to not loose all of your points at some point for some values of K. The damage needs to be minimized. We need to sacrifice the type of points that can make the rule will make the rule true and make sure that they are minimum. The incremental addition of points makes avoiding the rule inevitable and hence there is only one way of doing things at the end of the day.

27. A. Monsters [https://codeforces.com/gym/658336/problem/A] #30mins #1000  
    problem(what it looks like) : You want to do a procedure by selecting the maximum of the array and then reducing it by k and then you have to find the order in which the values become zero and return the indices in the order. The problem literally tells you what to do, just use a priority queue to achieve this but the twist is it takes very long too do it. This problem specifically tells you the solution and there is no faster wahy to simulate it then by the priority queue. The problem is tricky because you are not to find a better way to simulate just a faster way.  
    reduction(insight) : The problem only cares about when the valeus become zero so we can take all values to point such that the next operation will make them zero by doing value = value % k and everything that gets 0 to set it to k and then we can do the priority queue thing. Great problem learned a different technique to get things faster.  

28. C. Little Girl and Maximum Sum [https://codeforces.com/contest/276/problem/C] #1500
    problem(what it looks like) : It looks like a simple count frquency and then arrange the numbers like that. But to do the range query operations every single time is computationally expensive and you get a TLE error.  
    reduction(insight) : The range queries can be merged into one result at once by using the diff array. The diff array works by incrementing the diff[start] and decrementing the diff[end + 1] for each range query (start, end). The diff array ends up creating a differential of the original freq function and the first value is also the same as C. The diff array is differntial of the original function while the Prefix is the integration of the same function.

29. C. Two TVs [https://codeforces.com/contest/845/problem/C] #1500
    problem (what it looks like) : It looks like a complex resource sharing problem but it is not.  
    reduction (insight) : The problem is simple, the special condition isn't special it is just clarifying the already known conditions boundary case. Just simulate with bruteforce.

30. A. Carnival Wheel [https://codeforces.com/contest/2180/problem/A]  
    problem (what it looks like) : You have to find the maximum values of the prize of each spin. It looks hard because we can't say what could be maximum as the floor division function that gives the remainder is kind of funky.  
    reduction (insight) : You don't need to use mathematics to do it either. Realize it's a wheel values are going to repeat after l spins. Find the maximum after simulation the l spins, simple bruteforce.

31. B. Ashmal [https://codeforces.com/contest/2180/problem/B]  
    problem (what it looks like) : Actually there is no reduction you just have to simulate exactly what the problem is describing and not over engineer.  
    reduction (insight) : The insight is really that the bruteforce works so you don't need more sophisticated methods or overthink the problem.

32. C. XOR-factorization [https://codeforces.com/contest/2180/problem/C]  
    problem (what it looks like) : Actually the problem is what it looks like the solution is much more deep than you think it is going to be for a C. You have to distribute 1s and 0s of the original number to maximize the answer into K boxes. Such that the the XOR of the k numbers is the original. All the numbers have to be equal to or less than the original number  
    reduction (insight) : First : For odd values of K we can maximize by just outputing n k times as that is the maximum possible.
    Second : Everytime there is a 1 in the n we need that 1 to appear at an odd number of times in the K numbers and for 0 we can even stack 1s to maximize the eventual sum.
    Third : We are required to keep all the K numbers less than or equal to the original number, therefore when we are stacking 1s the number does not exceed n. Property of Binary Numbers : You can compare binary numbers from MSB to LSB and if one bit is set and the other is not then one with the set bit is going to be bigger than the other. We use the this property to part the K numbers into 2 groups Loose and Tight. Loose numbers are the ones that are already smaller than n and can't get greater than n as we are assigning bits of n and the tight numbers are the ones that are so far equal to n as we are assinging the bits of n. Because we only need this level of a sophisticated solution when K is even we know that we will need to skip a number when we are assigning ones of the original number always (as the number of 1s need to be odd), The skipped number will become loose. We need to make sure that we make as many loose numbers as possible and once they get loose we can stack 1s for 0s of the original numbers on the loose numbers to maximize our result. This way we can assign bits from MSB of the original to LSB of the original into K different numbers and maximize their sum. TADA !!!  

33. A. Blackslex and Password [https://codeforces.com/contest/2179/problem/A]  
    problem (what it looks like) : You need to comeup with a password such that any distance b/w the characters that is divisible by x can't have the same character. We need to find the minimal length n for which no such string can exist for a given k quantity of distinct characters.  
    reduction (insight) : You can have blocks of x adjacent characters of the same kind to maximize the length and then at max you will have a password of length k * x. so minimal n will be k * x + 1.

34. A. Olympiad Date [https://codeforces.com/contest/2091/problem/A] #13mins #800  
    problem : simple count the frequency of numbers and once they match to expected return how many total were counted before the match  
    insight : I have a resistance to bruteforce which I need to kill becuase I was thinking of a clever way to do the verification of expectated frequencies even though direct comparisor was also constant time.  

35. B. Team Training [https://codeforces.com/contest/2091/problem/B] #15mins #800  
    problem : maximize skill level and minimize total participants in a team that's all that had to be done.  
    insight : simple sorting and then creating teams. Again I was trying to solve a harder problem at firsy because of my hard problem mentality and resistance to bruteforce.

36. C. Combination Lock [https://codeforces.com/contest/2091/problem/C] #22mins #1000  
    problem : Had to find a permutation such that all cyclic shifts have exactly one number that is in the same position as it's value in the permutation.  
    insight : Let's fix a number at it's right position. Now to make a correct permutation no other numbers can be at their places. This turns the problem into a resource allocation problem where we have n - 1 agents and have n - 1 resources and each agent can consume 1 resource. There is an additional constraint that is they can't consume resources such that the distance between them and the resource is the same. If we carried out the resource allocation the best way possible even then if k agents are allocated some k resources for all the remaining agents the number of available resources will decrement by k no matter how you do it and that is actually ensured by the third constraint. We know an optimal way to allocate two resources to two agents such that only 2 are decremented from others option and that is by swapping the first and last element. This way we can optimally allocate resources in pairs of 2, and hence if n - 1 is odd there is no way to allocate the final resource and hence the soulution is not possible for n being odd.

37. D. Place of the Olympiad [https://codeforces.com/contest/2091/problem/D] #1200  
    problem : we need to select blocks in a row such that sum k squares are selected and minimize the cost which is the size of the largest block.  
    insight : To maximize capacity in a row we choose sum maximum block and then use as many of these as blocks as possible if we have space left then we use smaller blocks too. Larger the block more it's efficient in acquiring space that's why we first put the larger blocks and only when they can't fit we put the smaller blocks. Then we multiply it by the number of rows to check if it is enough. Now we can just use binary search on answers to guess in logarithmic time.
      
