## A Guide to K-Nearest Neighbors Classifier (KNN) in Python
August 30, 2020

### Table of Contents

* Introduction
* What is KNN?
* How does KNN work?
* Code
* Challenges
* Summary

### Introduction

In this guide, we will briefly explain the KNN classifier and show how to excute it in practice.

### What is KNN? 

KNN or K-Nearest Neighbors is a type of supervised learning that is non-parametric, requires no training, but has a high memory cost and inference time.  Given the model's high inference time, it is often used to a quick and dirty baseline for more complex models.

### A Simple Example of KNN Algorithm

Lets consider you are at party with a bunch of Marine Biolgists, Pedatricians, and Teachers.  You read a recent article about the salaries of these occupations and they are listed below:

* Job: Marine Biologist, Pediatrician, Teacher
* Salary: $70k, $200k, $50k

Somone you haven't met before comes up and talks to you and for whatever reason, you found out they earned an income of $230k annually.  After hearing their salary, one might think this person is a doctor out of the three potential occupations.  We arrive at this conclusion by finding the salary closest to $230k, and then we classify their occupation corresponding to that salary.  

* $230k - $70k = makes $150k more than an average Marine Biologist, not likely
* $230k - $200k = makes $30k more than an average Pedatrician, likely
* $230k - $50k = makes $180k more than an average Teacher, not likely

This logic of comparing the difference between salaries and then labeling the the new person is basically KNN. 

### How does KNN work?

The difference betwween data points in KNN algorithm is called a distance metric.  The distance metric calculates the distance or difference between the new data point with exisiting data points using geometry.  The new data point is then classified similary to the nearest exisiting data point(s), hence the term nearest neighbor.

For a 2-dimensional dataset, X = (x_1, x_2) the distance metric L would be a line as shown in the example above:

<img src="https://render.githubusercontent.com/render/math?math=L = |x_1, x_2|">

In higher dimensional datasets, the distance metric is called the L-norm and is written as:

<img src="https://render.githubusercontent.com/render/math?math=L^n = \sqrt(x_1^2 - x_2^2)">

When n=2, the L-norm is when we have two features X = (X1, X2) as presented above.

Another type of distance metric is cosine similarity.

### How to tweak the hyperparameter in KNN?


### KNN in Code



### Cross validation

### Write our own KNN

### References
https://sli0111.github.io/k-nearest-neighbors/
