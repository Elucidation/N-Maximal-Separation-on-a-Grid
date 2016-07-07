# N-Maximal-Separation-on-a-Grid
Finding a set of N filled cells on an NxN grid that maximizes the separation between every cell

## Problem formulation
Let's lay out the problem, we have an 8x8 grid of cells. 

|   |   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|
|   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |

We want to select 8 of those cells such that

* No two cells lie on the same row or column
* The sum of the distances between every cell is maximized