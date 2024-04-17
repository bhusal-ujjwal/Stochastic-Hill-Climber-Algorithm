# Stochastic Hill Climber Algorithm

Stochastic Hill Climber Algorithm
Implement Schastic Hill Climber Algorithm in either Mathematica or Python.
The algorithm description can be found in the related lectures.

Your algorithm must have these inputs:
Test function
Input domain of the test function
Dimension size
Number of iterations
Neighborhood size - number of generated solutions
Neighborhood radius - percentage of the hyperspace
The algorithm must provide at the output:
Best found value of objective function f(x)
The value of x of the best found f(x)
Convergence graph of the development of the f(x)


The goal of this algorithm is to find the global minimum of the selected test function.
The algorithm starts with one initial point (solution), which has randomly generated parameters (arguments). Around the starting point generates other points. Each solution has some solution quality (fitness) that depends on the test function. From all the newly generated points, the algorithm selects the best point (solution). The chosen point then becomes the initial point for the next iteration of the algorithm.

Be aware that each test function probably has different parameter bounds, and you have to ensure that all the newly generated points lie in the feasible space of solutions.
Once you implement the algorithm, you will need to apply it to the 5 test functions from the first Task. The algorithm has several features that you can adjust:

NP - The number of newly generated points in each iteration.
Radius - Radius in which new points are generated around the initial point.
maxIT - Maximal number of algorithm iterations.
The dimension size of each test function will be set as D=10.

You already know the minimal global value of each test function, so try to set the parameters for each test in a way that your algorithm will get to the minimal value as close as possible.

Compare the results with the Blind search algorithm (from Task 2) -- make a conclusion about which algorithm is more effective (the verbal assessment is enough)
For the comparison -- if you set both algorithms with the same setting (number of dimensions, iterations, test function), you can visually compare which algorithm achieved better results.
