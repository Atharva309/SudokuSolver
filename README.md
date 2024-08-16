# Sudoku Solver Using Genetic Algorithm

This project implements a Sudoku puzzle solver using a genetic algorithm. The goal is to solve a 9x9 Sudoku grid such that each row, column, and 3x3 subgrid contains all numbers from 1 to 9 exactly once.

## What is a Genetic Algorithm?

A Genetic Algorithm (GA) is a search heuristic inspired by the process of natural selection. It is used to find approximate solutions to optimization and search problems. The algorithm mimics the process of evolution with the following key steps:

1. **Initialization**: Create an initial population of potential solutions.
2. **Selection**: Evaluate the fitness of each solution and select the best ones.
3. **Crossover**: Combine pairs of solutions (parents) to create new solutions (offspring).
4. **Mutation**: Introduce random changes to some offspring to maintain genetic diversity.
5. **Replacement**: Replace the least fit solutions with the new offspring.

This iterative process continues over multiple generations, gradually evolving better solutions until a satisfactory result is achieved.

## How It Works

1. **Initialization**: Generate an initial population of Sudoku grids.
2. **Evaluation**: Assess how well each grid satisfies the Sudoku constraints.
3. **Selection**: Choose the best grids based on their fitness scores.
4. **Crossover and Mutation**: Apply genetic operators to create new grids.
5. **Termination**: Repeat the process until a valid Sudoku solution is found.

## Original Author

The project was originally developed by Christian Thomas Jacobs as part of the CS3M6 Evolutionary Computation module at the University of Reading.
The code is licensed under the MIT License, which permits open-source distribution and modification.

## How to Run

1. Clone the repository and set up the environment.
2. Run the provided script to start the genetic algorithm and solve the Sudoku puzzle.

## Conclusion

This project demonstrates the application of genetic algorithms to solve complex optimization problems, showcasing how evolutionary computation techniques can be effectively used in practical scenarios like Sudoku solving.
