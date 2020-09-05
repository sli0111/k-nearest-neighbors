## A Guide to K-Nearest Neighbors Classifier (KNN) in Python
August 30, 2020

### Table of Contents

* Introduction
* What is KNN?
* How does KNN work?

```markdown
Syntax highlighted code block

### Introduction - why do you want to learn it?

KNN is a simple classification model that is often used as a benchmark for more complex models.

### What is KNN? 

KNN is a model that compares a new data point with a known data set to predict or classify the new data point.  Lets consider some examples:

* you have a dataset 
* 

nonparametric, instance based, supervised learning, memory cost, define variables for the doc

### How does KNN work?

To compare a new data point with a known data set, KNN uses a distance metric.  The distance metric calculates the distance between the new data point with exisiting data points using geometry.  The new data point is then classified similary to the nearest exisiting data point(s), hence the term nearest neighbor.

For a 2-dimensional dataset, X = (X1, X2) the distance metric would be a line:

In general the distance metric is called the L-norm and is written as:

$$ L^n(x_1, x_2) = \sqrt(4) $$

When n=2, the L-norm is when we have two features X = (X1, X2) as presented above.

Another type of distance metric is cosine similarity.

### How to tweak the hyperparameter in KNN?


### KNN in Code



### Cross validation

### Write our own KNN
