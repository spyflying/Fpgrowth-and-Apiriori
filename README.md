# Fpgrowth-and-Apiriori
This is an implementation of Fpgrowth algorithm to dig out frequent patterns of a dataset of movielens.</br>
I implement FPGrowth with function FpGrowth. It requires a data structure of Fptree, which I implement with tree nodes.</br>
For performance valuation, I also implement Apiriori algorithm with function Apiriori to compare with FpGrowth.</br>
I test the algorithms on a subset of movielens. I make some preprocessment on the dataset to make it more suitable. It is included in movies.csv.</br>
frepat.py: The main function</br>
pipeline.yaml: Set environment</br>
Requirement: python2.7, pylab.py</br>
To run the algorithm, enter: python frepat.py pipeline.yaml</br>

