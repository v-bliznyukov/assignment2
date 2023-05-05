# Statistics Assignment 2
## Simulated Annealing implementation


The code in this repository is a step-by-step implementation of SA algorithm on Travelling Salesman Problem (TSP), where we need to find an optimal traveling path using SA 
between 30 most populated cities in Russia.

One can pre-define SA starting parameters such as temperature and speed of cooling. 
After that, the main function **annealing(cities_order, T_init, k)** produces the optimal path and saves the history of samples, 
temperatures and respective costs (or distances). Finally, a visualization (.mp4 video) is saved and can be downloaded.

To run the code one can simply execute the cells in the Task2 section.

This repository also contains examples of SA algorithm for Slow, Medium and Fast cooling speeds
