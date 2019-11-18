# A Python and Artificial Intelligence Program / Project

**This is a Python project from my early days as a Computer Science student**

_This programm was created for the sixth semester class Artificial Intelligence 
and is the final project for the class_

> #### Description of project
>
>>A Python script that solves the traveling salesman problem using genetic algorithms. The cities and the distances are predetermined but can also be randomly generated.

> #### Impementation of project
>
> 1. I create a random sized initial population, with random routes (the first city is the last one)
> 2. The user selects how many generations to run and the genetic algorithm begins
> 3. At the end of each generation the population is twice the size by adding routes using crossover, mutations and random routes
> 4. Survival of the fittest means that at the end of the generation, only half best will continue to exist at next generation
> 5. At each generation random routes are created in order for the algorithm not to stuck in local minimum solution
> 6. At each generation routes through crossover genetic function are generated:
>> Crossover is a simple process in which two parents produce a child. So I crossover few routes in pairs of the original population of each generation. 
Specifically in the crossover a small part of the 1st route (from the end) hangs on the 2nd route after first removing the cities of the 1st route we chose to cross over 2nd route. 
In this way a new crossover route emerges.
> 7. At each generation routes through mutation genetic function are generated:
>> Mutation is also a simple process where a parent gives birth to a child. In my algorithm I have implemented two modes of mutation where they are randomly selected. 
The first way is to select a small part of the parent and shuffle the cities of that part to create a new route. 
The second way is to select a small part of the parent and move it to another part of the parent so that a new route is created.

> #### About this project
>
> - The comments to make the code understandable, are within the .py archive
> - This project was written in IDLE, Python’s Integrated Development and Learning Environment.
> - This program runs for Python version 2.7
> - This repository was created to show the variety of the work I did and experience I gained as a student
>
