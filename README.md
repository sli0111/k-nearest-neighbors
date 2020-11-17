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

KNN or K-Nearest Neighbors is a type of supervised learning that is non-parametric, requires no training, but has a high memory cost and inference time.

### An example

Lets consider a list of jobs and their average salary.  

Job: Marine Biologist, Pediatrician, Teacher
Salary: $70k, $200k, $50k

If you were in a conversation with someone and they told you they earned a salary of $230k, then out of the three listed jobs one might think they are a doctor.  We arrive at this conclusion by finding the salary closest to $230k, and then we classify their occupation corresponding to that salary.  This logic is basically KNN where we compare the distance between the new datapoint to existing datapoints.

### How does KNN work?

The distance used in KNN to compare data points is simply called a distance metric.  The distance metric calculates the distance between the new data point with exisiting data points using geometry.  The new data point is then classified similary to the nearest exisiting data point(s), hence the term nearest neighbor.

For a 2-dimensional dataset, X = (X1, X2) the distance metric would be a line:

In general the distance metric is called the L-norm and is written as:

<img src="https://render.githubusercontent.com/render/math?math=L^n = ">

When n=2, the L-norm is when we have two features X = (X1, X2) as presented above.

Another type of distance metric is cosine similarity.

### How to tweak the hyperparameter in KNN?


### KNN in Code



### Cross validation

### Write our own KNN

### References
https://sli0111.github.io/k-nearest-neighbors/
