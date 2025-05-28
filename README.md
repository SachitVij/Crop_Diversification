# Objectives
The objective is to develop a decision support framework (DSF) to maximize crop yield, maximize profits, and minimize water usage over 1 season of crops. 
There is a tradeoff which has to be made among the above objectives, so to solve this problem we find the best solution without exploiting others.
# Approach
There is  a trade off between water resources used, yield for a crop, and crop yield. This is where multi-objective optimization (MOO) models find the most optimal solution.
Initially the area will be split equally between all the crops desired. Then the algorithm randomly divides the area and chooses the most optimal solution.
## Algorithms Used
1)NSGA-II Optimization: import from library pymoo==0.5.0
2)SPEA2: import from latest version of pymoo
