# BIS
Program 1: Particle Swarm Optimization (PSO)
Description
Particle Swarm Optimization (PSO) is a population-based optimization algorithm inspired by the social behavior of birds flocking and fish schooling. Each particle represents a potential solution and moves through the search space using its velocity, personal best position, and global best position. The particles collectively search for the optimal solution by continuously updating their positions and velocities.
Problem Statement
To implement Particle Swarm Optimization using Python to find the minimum value of a mathematical function by updating particle positions and velocities based on personal best and global best solutions.
Application Area
Mathematical Function Optimization: Finding the minimum value of \(f(x)=\sum x^2\).
Research Paper
Kennedy, J., & Eberhart, R. (1995). Particle Swarm Optimization. Proceedings of the IEEE International Conference on Neural Networks, 1942–1948.
Research Paper – PSOThe original PSO research introduced the algorithm for optimization using swarm behavior. 
DOI+1

Program 2: Ant Colony Optimization (ACO)
Description
Ant Colony Optimization (ACO) is a nature-inspired optimization algorithm based on the foraging behavior of ants. Artificial ants construct solutions by selecting paths based on pheromone trails and heuristic information such as distance. Shorter and better paths receive more pheromone, increasing their probability of being selected by future ants. Through repeated iterations, the algorithm identifies an optimal or near-optimal solution.
Problem Statement
To implement Ant Colony Optimization using Python to solve the Travelling Salesman Problem (TSP) by finding the shortest possible route that visits every city and returns to the starting city.
Application Area
Travelling Salesman Problem (TSP): Finding the shortest route among a given set of cities.
Research Paper
Dorigo, M., Maniezzo, V., & Colorni, A. (1996). Ant System: Optimization by a Colony of Cooperating Agents. IEEE Transactions on Systems, Man, and Cybernetics – Part B, 26(1), 29–41.
Research Paper – ACO

Program 3: Cuckoo Search (CS)
Description
Cuckoo Search (CS) is a nature-inspired optimization algorithm based on the brood parasitism of certain cuckoo species. It uses the concept of cuckoo eggs and host nests to generate and improve solutions. The algorithm uses Lévy flights to explore the search space and abandons a fraction of poor nests to maintain diversity and avoid local optima.
Problem Statement
To implement Cuckoo Search using Python to find the minimum value of a mathematical function through Lévy flights and nest replacement.
Application Area
Mathematical Function Optimization: Finding the minimum value of \(f(x)=\sum x^2\).
Research Paper
Yang, X. S., & Deb, S. (2009). Cuckoo Search via Lévy Flights. Proceedings of the World Congress on Nature & Biologically Inspired Computing, 210–214.
Research Paper – CS

Program 4: Grey Wolf Optimizer (GWO)
Description
Grey Wolf Optimizer (GWO) is a swarm intelligence algorithm inspired by the social hierarchy and hunting behavior of grey wolves. It models four levels of hierarchy: alpha, beta, delta, and omega. The three best solutions, alpha, beta, and delta, guide the remaining wolves during the search process. Their positions are updated collaboratively to explore and exploit the search space and obtain an optimal solution.
Problem Statement
To implement Grey Wolf Optimizer using Python to find the minimum value of a mathematical function by simulating the social hierarchy and hunting behavior of grey wolves.
Application Area
Mathematical Function Optimization: Finding the minimum value of \(f(x)=\sum x^2\).
Research Paper
Mirjalili, S., Mirjalili, S. M., & Lewis, A. (2014). Grey Wolf Optimizer. Advances in Engineering Software, 69, 46–61.
Research Paper – GWO

Program 5: Genetic Algorithm (GA)
Description
Genetic Algorithm (GA) is an optimization technique inspired by natural selection and genetics. It maintains a population of candidate solutions called individuals. The fitness of each individual is evaluated, and fitter individuals are selected for reproduction. Crossover combines parent solutions to produce offspring, while mutation introduces random changes to maintain genetic diversity. This process continues over successive generations to obtain an optimal solution.
Problem Statement
To implement a Genetic Algorithm using Python to find the maximum value of a mathematical function by applying selection, crossover, and mutation over successive generations.
Application Area
Mathematical Function Optimization: Finding the maximum value of \(f(x)=x\sin(10\pi x)+1\).
Research Paper
Mühlenbein, H., Schomisch, M., & Born, J. (1991). The Parallel Genetic Algorithm as Function Optimizer. Parallel Computing, 17(6–7), 619–632.
Research Paper – GA

Program 6: Parallel Cellular Algorithm
Description
Parallel Cellular Algorithms are inspired by cellular automata and parallel computing. A population of candidate solutions is arranged in a cellular grid, where each cell interacts with its neighboring cells. Each cell updates its state based on neighborhood information and predefined rules. These local interactions allow information to spread throughout the grid, improving the solutions and enabling efficient exploration of the search space.
Problem Statement
To implement a Parallel Cellular Algorithm using Python to find the minimum value of a mathematical function by arranging candidate solutions in a cellular grid and updating their states based on neighboring cells.
Application Area
Mathematical Function Optimization: Finding the minimum value of \(f(x)=\sum x^2\) using local neighborhood interactions.
Research Paper
Gordon, V. S., & Whitley, D. (1993). Serial and Parallel Genetic Algorithms as Function Optimizers. Proceedings of the International Conference on Genetic Algorithms.

Related research on cellular genetic algorithms and function optimization:
Cellular Genetic Algorithms as Function Optimizers – Research PDF
References – Quick List
Program	Research paper
PSO	Kennedy & Eberhart (1995)
ACO	Dorigo, Maniezzo & Colorni (1996)
CS	Yang & Deb (2009)
GWO	Mirjalili et al. (2014)
GA	Mühlenbein et al. (1991)
Parallel Cellular	Gordon & Whitley (1993)
