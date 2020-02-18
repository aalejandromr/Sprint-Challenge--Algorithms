#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(3^n) ? O(2^n)

We are exponentially incresing n as the input increases.

b) O(n^2)

While the first loop is iterating for every n, the second loop is going to iterate n times n


c) O(n)

Because we only have linear operations, while we are taking a lot of memory space, the run time stays at n.

## Exercise II

for building in buildings:
  if building.floor < f:
    for egg in eggs:
      dropped_egg += 1

O(n log n)

n Log n because we are mapping over the whole first array, but then we are minimizing the times we iterate over the first array x times
