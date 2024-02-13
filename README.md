# CT421_A1_Assignment1-

Part A:
----------------------------------------
(i) One Max Problem
Solution - Genetic Algorithms One Max Problem 

This genetic algorithm uses a population of 30 bit-long ints. The target string for this algorithm is a bit-string that has 1 in each position, the algorithm uses a randomnly generated population, and using muatation, one-point crossover and tournament selection on each generation. It uses matplotlib to generate a graph that plots the average fitness between each generation, with the fitness being how many 1's are present.

(ii) Evolving to a Target String
Solution - Genetic Algorithms Evolving to a String

This is an extension of the One Max Problem, except this time the target string is set as a random string of 30 integers. Once again a random population is generated and the fitness is equated to the amount of bits it has in common with the target string.

(iii) Deceptive Landscape
Solution - Genetic Algorithms Deceptive Landscape 

This GA is an extension of the One-max algorithm. This GA is used to illustrate some of the shortcomings of the Genetic Algorithm. We insert a second target alongside the 30 bit string with ones. We also reward a bit-string of all 0s i.e. 0 base 10. A bit-string of 0 is scored double the fitness of a bit-string with all ones.

It is observed that the GA never achieves the global optimum of 0. Even if a value of 0 is present in the initial random population, it will be lost in the next generation due to mutation and crossover.

This is also an extension of the One Max Problem. This is used to show how an GA might have a shortfall in terms of determining the fittest bit-string. I haev seen that the GA 
