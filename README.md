# Ozone-Level-Detection
Logistic Regression/Neural Networks

## Overview

In this assignment, we aim to evaluate the performance of logistic regression and compare it with multi-layer neural networks for a classification problem. Specifically, we will consider the problem of detecting ozone levels in the atmosphere. The dataset includes 2,536 data points collected hourly, with 73 features each.

**The dataset is available in the file Ozone Level Detection.data.**


## Preprocessing:

As you can see in the dataset, there are some Missing Values. Research possible solutions to handle this issue, choose the best method for this dataset, and implement it.

Additionally, to split the data into training and testing sets, use the k-fold cross-validation method with K=3. Report the mean and standard deviation of the accuracy obtained for different states.

## Logistic Regression:

In this section, our goal is to predict ozone levels using the logistic regression method. Try to optimize the parameters using gradient descent and implement the cost function accordingly. Explain the role of regularization in preventing underfitting and overfitting when learning the parameters. Use Accuracy as the evaluation metric for your model.

## Neural Networks:

At this stage, we aim to solve the prediction problem using a multi-layer neural network. You might experiment with different structures in terms of the number of layers, number of neurons in each layer, learning rates, etc. Make sure to test these parameters with different values, compare the results, and report them. Use Accuracy as the evaluation metric for your model. Demonstrate that your model does not suffer from underfitting or overfitting issues.
