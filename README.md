# Fpgrowth-and-Apiriori
This is an implementation of Fpgrowth algorithm to dig out frequent patterns of a dataset of movielens.</br>
I implement FPGrowth with function FpGrowth. It requires a data structure of Fptree, which I implement with tree nodes.\n
For performance valuation, I also implement Apiriori algorithm with function Apiriori to compare with FpGrowth.\n
I test the algorithms on a subset of movielens. I make some preprocessment on the dataset to make it more suitable. It is included in movies.csv.\n
frepat.py: The main function\n
pipeline.yaml: Set environment\n
Requirement: python2.7, pylab.py\n
To run the algorithm, enter: python frepat.py pipeline.yaml\n

