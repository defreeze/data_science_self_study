This directory contains the finished projects for the kaggle feature engineering course found here: https://www.kaggle.com/learn/feature-engineering


Lesson 1: What is Feature Engineering?

- determine which features are the most important with mutual information
- invent new features in several real-world problem domains
- encode high-cardinality categoricals with a target encoding
- create segmentation features with k-means clustering
- decompose a dataset's variation into features with principal component analysis

A Guiding Principle of Feature Engineering
For a feature to be useful, it must have a relationship to the target that your model is able to learn. Linear models, for instance, are only able to learn linear relationships. So, when using a linear model, your goal is to transform the features to make their relationship to the target linear.

The key idea here is that a transformation you apply to a feature becomes in essence a part of the model itself.

--------------------------------------------------------------------------------------

Lesson 2: Mutual Information
A great first step when encountering a new dataset is to contruct a ranking with a feature ulility metric (measure associations between a feature and target).

Mutual information is a great general-purpose metric and especially useful at the start of feature development when you might not know what model you'd like to use yet. It is:

- easy to use and interpret,
- computationally efficient,
- theoretically well-founded,
- resistant to overfitting, and,
- able to detect any kind of relationship

Mutual information describes relationships in terms of uncertainty. The MI between two quantities is a measure of the extent to which knowledge of one quantity reduces uncertainty about the other. 
