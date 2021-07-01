# Genetic-Algorithm 
In this notebook, I have implemented different strategies of GA methods.   

# Details:
The Genetic Algorithm is a stochastic global search optimization algorithm.
The algorithm uses analogs of a genetic representation (bitstrings), fitness (function evaluations), genetic recombination (crossover of bitstrings), and mutation (flipping bits).

The algorithm works by first creating a population of a fixed size of random bitstrings. The main loop of the algorithm is repeated for a fixed number of iterations or until no further improvement is seen in the best solution over a given number of iterations.

One iteration of the algorithm is like an evolutionary generation.

First, the population of bitstrings (candidate solutions) are evaluated using the objective function. The objective function evaluation for each candidate solution is taken as the fitness of the solution, which may be minimized or maximized.

Then, parents are selected based on their fitness. A given candidate solution may be used as parent zero or more times. A simple and effective approach to selection involves drawing k candidates from the population randomly and selecting the member from the group with the best fitness. This is called tournament selection where k is a hyperparameter and set to a value such as 3. This simple approach simulates a more costly fitness-proportionate selection scheme.

Different strategies of GA methods:
- Parents selection
- Corssover
- Mutation
- Fitness function (objective function)
