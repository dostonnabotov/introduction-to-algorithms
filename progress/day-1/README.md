# Day 1 - 07/12/2023

## Topics Covered

O-notation, Ω-notation and Θ-notation

## What I learned

Today I revised this as a refreshment.

Big O Notation (O-notation) is used to describe the upper bound (or **the worst-case scenario**) of the algorithm.

Omega Notation (Ω-notation) is used to describe the lower bound (or **the best-case scenario**) of the algorithm.

Theta Notation (Θ-notation) is used to describe the tight bound (or **the average-case scenario**) of the algorithm.

In my opinion, the best example to describe the scenarios would be the `Bubble Sort` algorithm. At its worst case, it performs Big O of `O(n^2)`, which means it would have to sort all the elements.

In the best-case scenario (which is very rare), it performs Omega `Ω(n)`, which states that elements are already sorted and the algorithm has to interate only once to find out that.

In the average-case scenario, the performance of the algorithm would range from `Θ(n)` to `Θ(n^2)`, meaning that elements are partially sorted.

Because we usually consider the worst-case scenario when implementing the algorithm, Big O notation has more popularity than its two other counterparts.
