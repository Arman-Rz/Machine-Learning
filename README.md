# Machine Learning

This repository contains Python implementation of five machine learning algorithms from scratch to enhance understanding of their inner workings. Additionally, a dataset is used to evaluate the performance of the algorithms. In the dataset we have 10000 datapoints where each datapoint contains 10 features and one output column which is +1 or -1. For evaluation, the Zero-One-Loss is used.

Every algorithm has a preprocessing data section in which the data is first normilized, shuffled and splitted in four separate datasets namely TrainData, TrainLabel, TestData and TestLabel.

## List of Algorithms:
  - Perceptron
  - Kernel Perceptron
  - Support Vector Machines (SVMs) using the Pegasos algorithm
  - kernelized Pegasos with the Gaussian and the polynomial kernels for SVM
  - Regularized logistic classification
