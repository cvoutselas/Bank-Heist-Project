# Bank-Heist-Project
Given 24 hours, I created an algorithm to try to rob as many banks as possible for the most amount of money and return to the getaway point in time. 

# Description
Given list of bank locations, how much money each one holds and the time it would take to rob each one, you need to apply your hard-won algorithm knowledge to make as much profit as possible! I bet you didn't think that data science could be this profitable!

You will design and write a solution to an NP-Had algorithm to this problem

You will need to apply all the knowledge learned up to now to get the best possible result at this task given a large list of banks and 3 minutes to run your algorithm.

# Rules
Your run can start anywhere on the map but it has to end at the helicopter escape zone: coordinates (0,0)

If you try to rob too many banks and can't get to the helicopter in 24 hours, you get caught and go to jail. Your solution is a list or array of integers (eg. [580, 433, 24, 998]) where the numbers are the IDs of each banks. The ID of each bank is their index (their row index).

You travel between banks at 30 km/h. You have to travel from one bank to the next!

Remember the formula to calculate the distance between two points. The coordinates are in kilometers. So (1, 1) and (1, 2) are one kilometer apart. This would take 1 / 30 hour = 2 minutes to travel Your solution should be an approximative/heuristic algorithm

This problem is NP-Hard, you won't find a fast enough algorithm that has the perfect solution It doesn't need to find the best solution Find the best solution you can! Your solution has to run on a common laptop in under 3 minutes for the 10,000 cities dataset

You can use everything you want to achieve this: Use numpy, pandas, functions, algorithms You can use parallelism Use optimied libraries (pandas, numba, scipy, etc.) Test your code on small subsets of the data so they run fast Then scale your code up to bigger chunks of the data Your input is a pandas dataframe with the bank data. Your output is a list of bank IDs in order that you rob them
