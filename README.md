
# Algorithms First Review

## Review

Incorrect complexity of NN

Incorrect diagram of O(n log n)

# NN TSP Review Assignment

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

