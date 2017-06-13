# Fpgrowth-and-Apiriori
This is an implementation of Fpgrowth algorithm to dig out frequent patterns of a dataset of movielens.
I implement FPGrowth with function FpGrowth. It requires a data structure of Fptree, which I implement with tree nodes.
For performance valuation, I also implement Apiriori algorithm with function Apiriori to compare with FpGrowth.
I test the algorithms on a subset of movielens. I make some preprocessment on the dataset to make it more suitable. It is included in movies.csv.
frepat.py: The main function
pipeline.yaml: Set environment
Requirement: python2.7, pylab.py, 
To run the algorithm, enter: python frepat.py pipeline.yaml

