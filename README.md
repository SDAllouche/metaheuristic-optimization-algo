# Metaheuristic Optimization Algorithm

## Introduction
In this study, we will look at different ways to find the best solution by adjusting the settings of the problem. The methods that used in this study will be implemented using Python Programmation language. Those are: Simulated Annealing, Tabu Search and Genetic Algorithms. In addition we will show a comparison of those methods.

## 1. Simulated Annealing

### 1.1	What is Simulated Annealing ?

Simulated annealing (Cernyt’, 1985; Kirkpatrick et al., 1983) is inspired by an anal- ogy between the physical annealing of solids (crystals) and combinatorial optimization problems. In the physical annealing process, a solid is first melted and then cooled very slowly, spending a long time at low temperatures, to obtain a perfect lattice structure corresponding to a minimum energy state. SA transfers this process to local search al- gorithms for combinatorial optimization problems. It does so by associating the set of solutions to the problem attacked with the states of the physical system, the objective function with the physical energy of the solid, and the optimal solutions with the mini- mum energy states.
Simulated annealing randomly chooses a solution x′ in the neighborhood of the current solution x. If x′ is better than x, then x′ is accepted and becomes the current solution, whereupon the process repeats. If x′ is no better than x, x′ is nonetheless accepted with a certain probability p.

### 1.2 Schema

![image](https://github.com/SDAllouche/metaheuristic-optimization-algo/assets/102489525/d36579e5-0d47-41ee-9b25-f82b24fb59d3)

### 1.3	HIMMELBLAU function
We’re going to apply this algorithm to the HIMMELBLAU function 4.2, it is a multi- modal function, used to test the performance of optimization algorithms. Were going to try finding the x and y for f equal to 0.
The function is defined:   
                                  $\ f (x, y) = (x^2 + y − 11)^2 + (x + y^2 − 7)^2$



