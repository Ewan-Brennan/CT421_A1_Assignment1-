# CT421_A1_Assignment1-

Part A:
----------------------------------------
(i) One Max Problem - Connor Adams
Solution - Genetic Algorithms One Max Problem 

This genetic algorithm uses a population of 30 bit-long ints. The target string for this algorithm is a bit-string that has 1 in each position, the algorithm uses a randomnly generated population, and using muatation, one-point crossover and tournament selection on each generation. It uses matplotlib to generate a graph that plots the average fitness between each generation, with the fitness being how many 1's are present.

(ii) Evolving to a Target String - Connor Adams
Solution - Genetic Algorithms Evolving to a String

This is an extension of the One Max Problem, except this time the target string is set as a random string of 30 integers. Once again a random population is generated and the fitness is equated to the amount of bits it has in common with the target string.

(iii) Deceptive Landscape - Ewan Brennan
Solution - Genetic Algorithms Deceptive Landscape 

This is also an extension of the One Max Problem. This is used to show how an GA might have a shortfall in terms of determining the fittest bit-string. Alongside the target of the 30 bit string, we also set a target of all 0's, this is then given a double score to the fitness of a bit string with all 1's. The output for my assignment shows that once it reaches the optimum 30 bit string of all 0's, it determines it to be the fittest candidate and returns it with a 60-bit value, which highlights the potential shortfall of the algorithm.

Part B: 
----------------------------------------
Bin-Packing problem - Ewan Brennan
Solution - Genetic Algorithms Bin-packing problem

This algorithm is designed to tackle famous bin-packing problem. The solution is designed to find the corect balance between using the lowest amount of bins possible to fit all of the items in it but also to avoid the overzealous use of partially filled bins. My aim was to create an algorithm that had efficient modes of determining the fitness of individual items while also giving it an effective way to sort these bins by weight in order to develop the most efficient solution 
