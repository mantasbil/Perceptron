# Perceptron with training

This Jupyter Notebook presents a single perceptron training project. 

The perceptron and its training process is coded from scratch. Weights are trained via the backpropagation method.
Perceptron is trained on two datasets from UCI Machine Learning repository - [Iris](https://archive.ics.uci.edu/dataset/53/iris) and [Breast Cancer](https://archive.ics.uci.edu/dataset/15/breast+cancer+wisconsin+original). Since the Iris dataset contains three classes and perceptron is used only for classifying objects into two classes, only 'Iris versicolor' and 'Iris virginica' classes were used.

Two types of activation functions are considered:
1. Step activation function
2. Sigmoid activation function

Classification accuracy and loss is calculated for each epoch and the values are compared for both types of activation functions.

Since sigmoid activation function produced more stable classification results for both datasets, only this function was used for data validation.

High classification accuracy was observed for both train and validation subsets of the two datasets. However slight overfitting was starting to appear for the breast cancer dataset after 20 epochs.

This project could be further improved by evaluating the effect of learning rate for the classification.
