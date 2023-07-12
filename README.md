<h1>Eight Queens Problem Solved Using Genetic Algorithm</h1>

<p>GA works on the population of individual, in other words the group of individuals is known as population. The GA
generates population by selecting random individuals according to their fitness. Fitness is a value who determines
the most fitted individual in the current population to be selected as a parent for next generation. In other words it is
a value who determines the performance of GA towards best solution. The fitness function varies from problem to
problem. Individuals go through a process of selection after assigning the fitness value for the survival of fittest.
The eight queens puzzle is the problem of putting eight chess queens on an 8×8 chessboard such that none of them
is able to capture any other using the standard chess queen’s moves. The queens must be placed in such a way that
no two queens would be able to attack each other. Thus, a solution requires that no two queens share the same row,
column, or diagonal.

Representation: [2 4 6 8 3 1 7 5]
Population Generation: Generate 4 individuals randomly
Parent Selection: Using Roulette Wheel
Cross Over and Mutation: Random
Evaluation Function: Number of non attacking pairs
</p>
