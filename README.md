# Travelling Salesman Problem using Dynamic Programming

This repository contains an implementation of dynamic programming to find the shortest path from the travelling salesman problem (TSP). In this case, the salesman needs to visit each city once without returning to the start city.

## Getting Started

Replace the distance_matrix variable value with the distances between each pair of cities in square matrix form.
```python
distance_matrix = [
    [0, 328, 259, 180, 314, 294, 269, 391],
    [328, 0, 83, 279, 107, 131, 208, 136],
    [259, 83, 0, 257, 70, 86, 172, 152],
    [180, 279, 257, 0, 190, 169, 157, 273],
    [314, 107, 70, 190, 0, 25, 108, 182],
    [294, 131, 86, 169, 25, 0, 84, 158],
    [269, 208, 172, 157, 108, 84, 0, 140],
    [391, 136, 152, 273, 182, 158, 140, 0],
]
```
Then pick a start city.
```python
start_city = 0
```
To run the python program, execute this command in terminal.
```bash
python main.py
```
