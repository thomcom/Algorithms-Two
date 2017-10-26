
# Algorithms First Review

Revisit

Incorrect complexity of NN

Incorrect diagram of O(n log n)

# NN TSP Review

1. How long to run on set of size 4? 10? 20?
2. How long to run NN on same sets?
3. How close is NN's solution to the optimal?
4. How can you improve NN?

# kNN TSP assignment

kNN

k = number of neighbors to explore

# Terms

- Computability

[Computability](https://en.wikipedia.org/wiki/Computability)

- Tractability

Tractability refers to the question as to whether a problem is easily solved in practice. Algorithms that find optimal solutions become intractable quickly on large datasets. In order to find optimal solutions tractably, complicated and unintuitive algorithms have been developed. In order to find near-optimal solutions quickly, random or partial algorithms have been created.

- Reduction of complexity of specific algorithms

FFT reduces from O(n^2) to O(n log n) via algorithm. This doesn't prove that every O(n^2) algorithm can be reduced to O(n log n).

Finding the nearest pair of points among a set of 2d points is obviously O(n^2), but using a [divide and conquer](https://en.wikipedia.org/wiki/Divide_and_conquer_algorithm) algorithm reduces the complexity to O(n log n) as well.

Finding the closest pair of points: Obviously O(n^2), can be simplified to O(n log n), then again to O(n) with randomization.

# Case study in binary trees

## Trees

## Binary trees

### Binary tree insertion

### Binary tree lookup (traversal)

### Binary tree deletion

### Binary tree rebalancing

## Self balancing binary trees

### B-tree

### Red-black tree

# Review algorithm theories:

Decideability

Tractability

Complexity

Decision problems:

Given a set of cities, is there an algorithm that will compute the shortest path connecting those cities in a closed loop?

O(n!) = yes

O(n^x) = no

P = polynomial time algorithm solutions

NP = not polynomial time algorithm solutions

[P = NP?](https://en.wikipedia.org/wiki/P_versus_NP_problem)



Algorithms:

 a. BFS, DFS, Hashes, Binary trees, and large datasets.
 
 b. Search and Function Optimization: Greedy, Gradient Descent, and A\*

 g. Complexity, computability, and branching factor

 c. Google's Map/Reduce and indexing

Scheduling

Minimum Spanning Tree - Kruskal's Algorithm

Traveling Salesman

N-Satisfiability

Convolution

1. Look up a solution to recursively multiply two integers and implement it.

