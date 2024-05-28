# Practices for ITMO Algorithms course

## [Practical task №1: Experimental time complexity analysis.](https://github.com/andreishestakov13/Alghoritms.-Labs/blob/main/Practical_task_1.ipynb)
* Goal:

Experimental study of the time complexity of different algorithms.

* Formulation of the problem:

For each n from 1 to 2000, it is necessary to measure the average computer execution time of programs for the algorithms of sum, multiplication, Horner's method, Bubble sort, Quick sort, Timsort and also for multiplying square matrices. Then it is necessary to plot the dependence of the program execution time on the amount of input data and compare it with the theoretical value.

## [Practical task №2: Algorithms for unconstrained nonlinear optimization. Direct methods.](https://github.com/andreishestakov13/Alghoritms.-Labs/blob/main/Practical_task_2.ipynb)
* Goal:

The use of direct methods (one-dimensional methods of exhaustive search, dichotomy, golden section search; multidimensional methods of exhaustive search, Gauss (coordinate descent), Nelder-Mead) in the tasks of unconstrained nonlinear optimization.

* Formulation of the problem:

1. Implement one-dimensional enumeration, dichotomy and golden section methods for approximate search x: f(x) → min for cubic and sinusoidal functions, as well as the function f(x) = |x-0.2|.
2. In the second part of the laboratory work, it is necessary to choose random α and β values between 0 and 1, then, using these values, generate a random array of noisy data according to the rule yk = αxk + β + δk and approximate the obtained data with linear and rational functions using the method of least squares by numerically minimizing the function. In this part of the work, it is necessary to use the methods of enumeration, Gauss and Nelder-Mead.

## [Practical task №3: Algorithms for unconstrained nonlinear optimization. First- and secondorder methods.](https://github.com/andreishestakov13/Alghoritms.-Labs/blob/main/Practical_task_3.ipynb)

* Goal:

The use of first- and second-order methods (Gradient Descent, Non-linear Conjugate Gradient Descent, Newton’s method and Levenberg-Marquardt algorithm) in the tasks of unconstrained nonlinear optimization.

* Formulation of the problem:

To solve the minimization problem, use the methods of Gradient Descent, Conjugate Gradient Descent, Newton’s method and Levenberg-Marquardt algorithm. Visualize the data and the approximants obtained in a plot separately for each type of approximant so that one can compare the results for the numerical methods used. Analyze the results obtained (in terms of number of iterations, precision, number of function evaluations, etc.) and compare them with those from Task 2 for the same dataset.

## [Practical task №4: Algorithms for unconstrained nonlinear optimization. Stochastic and metaheuristic algorithms.](https://github.com/andreishestakov13/Alghoritms.-Labs/blob/main/Practical_task_4.ipynb)

* Goal:

The use of stochastic and metaheuristic algorithms (Simulated Annealing, Differential Evolution, Particle Swarm Optimization) in the tasks of unconstrained nonlinear optimization and the experimental comparison of them with Nelder-Mead and Levenberg-Marquardt algorithms.

* Formulation of the problem:

To solve the minimization problem, use Nelder-Mead algorithm, Levenberg-Marquardt algorithm and at least two of the methods among Simulated Annealing, Differential Evolution and Particle Swarm Optimization. Visualize the data and the approximants obtained in a single plot. Analyze and compare the results obtained (in terms of number of iterations, precision, number of function evaluations, etc.). Choose at least 15 cities in the world having land transport connections between them. Calculate the distance matrix for them and then apply the Simulated Annealing method to solve the corresponding Travelling Salesman Problem. Visualize the results at the first and the last iteration.

## [Practical task №5: Algorithms on graphs. Introduction to graphs and basic algorithms on graphs.](https://github.com/andreishestakov13/Alghoritms.-Labs/blob/main/Lab_5.ipynb)

* Goal:

The use of different representations of graphs and basic algorithms on graphs (Depth-first search and Breadth-first search).

* Formulation of the problem:

1. Generate a random adjacency matrix for a simple undirected unweighted graph with 100 vertices and 200 edges (note that the matrix should be symmetric and 
contain only 0s and 1s as elements). Transfer the matrix into an adjacency list.  Visualize the graph and print several rows of the adjacency matrix and the 
adjacency list.
2. Use Depth-first search to find connected components of the graph and Breadthfirst search to find a shortest path between two random vertices. Analyse the results obtained.
3. Describe the data structures and design techniques used within the algorithms.

## [Practical task №6: Algorithms on graphs. Path search algorithms on weighted graphs.](https://github.com/andreishestakov13/Alghoritms.-Labs/blob/main/Lab_6.ipynb)

* Goal:

The use of path search algorithms on weighted graphs (Dijkstra's, A* and Bellman-Ford algorithms)

* Formulation of the problem:

1. Generate a random adjacency matrix for a simple undirected weighted graph of 100 vertices and 500 edges with assigned random positive integer weights (note that the matrix should be symmetric and contain only 0s and weights as elements). Use Dijkstra's and Bellman-Ford algorithms to find shortest paths between a random starting vertex and other vertices. Measure the time required to find the paths for each algorithm. Repeat the experiment 10 times for the same starting vertex and calculate the average time required for the paths search of each algorithm. Analyze the results obtained.
2. Generate a 10x20 cell grid with 40 obstacle cells. Choose two random nonobstacle cells and find a shortest path between them using A* algorithm. Repeat the experiment 5 times with different random pair of cells. Analyze the results obtained.
3. Describe the data structures and design techniques used within the algorithms.

## [Practical task №7: Algorithms on graphs. Tools for network analysis.](https://github.com/andreishestakov13/Alghoritms.-Labs/blob/main/Practical_task_7.ipynb)

* Goal:

The use of the network analysis software Gephi.

* Formulation of the problem:

1. Download and install Gephi from https://gephi.org/.
2. Choose a network dataset from https://snap.stanford.edu/data/ with number of nodes at most 10,000. You are free to choose the network nature and type (un/weighted, un/directed).
3. Change the format of the dataset for that accepted by Gephi (.csv, .xls, .edges,  etc.), if necessary.
4. Upload and process the dataset in Gephi. Check if the parameters of import and data are correct.
5. Obtain a graph layout of at least two different types.
6. Calculate available network measures in Statistics provided by Gephi.
7. Analyze the results for the network chosen.
While performing the work, screenshot the main steps you are doing and insert in 
the report.

## [Practical task №8: Practical analysis of advanced algorithms.](https://github.com/andreishestakov13/Alghoritms.-Labs/blob/main/Lab_8.ipynb)
* Goal:

Practical analysis of advanced algorithms

* Formulation of the problem:

1. Choose two algorithms (interesting to you and not considered in the course) from the above-mentioned book sections.
2. Analyze the chosen algorithms in terms of time and space complexity, design technique used, etc. Implement the algorithms and produce several experiments. 
Analyze the results..
