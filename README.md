# Principal Component Analysis

## Discription  
This repository represents teh calculation of Principal Component Analysis on Python.

We will need the following Libraries that will need to be imported.

1. numpy
2. matplotlib    
3. scipy
4. sklearn.linear_model
5. sklearn.decomposition
6. statsmodels.api
7. itertools


This program is implemented in [Python 3.7](https://www.python.org/downloads/release/python-377/). 

### Introduction:

In data science, machine learning, and statistics, Principal Component Analysis (PCA) is a dimensionality reduction method often used to reduce the dimensionality of large data sets by transforming a large set of variables into a smaller one that still contains most of the information in the large set.

Reducing the number of variables in a data set naturally comes at the expense of accuracy. Still, the trick to dimensionality reduction is to trade a little accuracy for simplicity. Smaller data sets are easier to explore and see, making it much easier for machine learning algorithms to analyze data since they don't have to deal with as many variables.
 
PCA finds directions of maximal variance in the data. It finds mutually orthogonal directions. Mutually orthogonal means it's a global algorithm. Global means that all the new directions and features they find must be orthogonal. This is a significant global constraint.
