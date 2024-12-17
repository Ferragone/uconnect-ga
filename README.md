# uconnect-ga using Genetic Algorithm

## Моделювання та аналіз генетичного алгоритму в задачі максимізації функції багатьох змінних
Студент: ІКМ-М223А Тихоненко Артем Олександрович

## About

The **genetic algorithm** is an optimization technique inspired by Charles Darwin’s principle of natural evolution. Much like natural selection in the wild, this algorithm seeks out the fittest individuals to reproduce and shape the next generation. In this project, these individuals are represented as strings, and their unique traits are the letters within those strings. Collectively, they form a dynamic population that evolves toward a target solution. This project explores the essential stages of a genetic algorithm, each contributing to the refinement of the population over time:

**Initial population** The journey begins by generating a diverse pool of individuals, each with unique traits. Here, individuals are represented by strings composed of randomly generated letters, each matching the length of the target string. This randomness seeds the population with variety, a critical component for evolutionary potential.

**Selection** Not all individuals are equal in fitness. This phase evaluates how closely each string resembles the target and assigns a fitness score accordingly. The fitter the individual, the higher the probability it will be selected to contribute its traits to the next generation.

**Crossover** In this phase, the fittest individuals are paired to produce offspring by combining their traits. Just as in nature, crossover blends portions of each parent’s string, giving rise to new individuals that inherit a mix of characteristics, increasing the chances of discovering the optimal solution.

**Mutation** To maintain diversity and avoid stagnation, a small dose of randomness is introduced through mutation. With a low probability, the traits (letters) of new offspring are altered, allowing for unexpected variations. A higher mutation rate leads to more frequent changes, potentially accelerating discovery but risking divergence from the optimal path.

## Technologies Used

- This app is built with NextJS and TailwindCSS
- This project utilizes a serverless function to handle form validation