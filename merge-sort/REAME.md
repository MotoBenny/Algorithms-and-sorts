# Merge sort

A merge sort algorithm breaks down a problem into multiple small problems recursively.
Until the problems can be solved in a single opperation, than combines the solutions together
to reach a solution to the larger whole problem. 

Merge sort has a O(n * log(n)) running time. 

### Steps
    1. Split the list into halves
    2. Continue recursively splitting the list, until we have sub lists, of just 2 values.
    3. Perform a simple sort on the smaller lists.
    4. Combine sublists into single sorted list.


### Example list. [5, 1, 7, 8, 2, 5, 9, 3]

Split the first list in half.

[img](Img1.png)

Recursively call the algorithm to continue splitting the sublists into smaller lists.

[img](img2.png)

At this point our input list, is split as far as we can split it. 

[img](img3.png)