# StochastocOptimization
Here you can find codes for stochastic problems solved by GUROBI/Python interface.
** Having 'gurobipy' installed for Python interface is necessary.

## MonteCarloApproximation
Problem: A company would like to determine the number of phisical servers type 1,2,3 that must be purchased right now. After the realization of monthly demand, virtual servers can handle the demand as well as physical ones. The company wants to determine the total number of physical and virtual servers of each type that need to be purchased.
The distribution of demand is normal with parameters N1(75,8), N2(8,3), N3(18,2).
Each server is used for only one unit of demand.
The company has limitations of total invested budget and occupied physical space which are $1100, 90 respectively.
The cost of each virtual server is 8,20,33. The investment cost for each physical server is 7,12,25. Also, each physical server occupies 1,5,4 units.
A simple MonteCarlo approximation is used to create 100 scenarios.

Note that after the realization of demand, y can be chosen so that the whole demand is covered.

## L-Shaped Method
Read the pdf file named L-ShapedMethod to get the steps of the algorithm and an example problem used in the code.

