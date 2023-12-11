# Wilsons-random-grid-graph
Wilson's Algorithm is an algorithm to generate a uniform spanning tree using a loop erased random walk.  In this modification specific for grid graphs I've added the  possibility of introducing cycles by adding a number or independently and randomly selected edges.

# Usage Example


```
gen = WilsonGridGraphGeneratorWLoops(10, 10, 3)
```

Creates a class object for a spanning tree of a 10 by 10 grid graph plus 3 randomly drawn edges which will naturally form 3 circuits.

```
A = gen.generate_adjacency()
```
This method will generate the adjacency matrix of the random grid graph in list form.

```
print(gen)
```
Will print a string version of the generated graph for visualization.
