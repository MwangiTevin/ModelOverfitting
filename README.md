 Classifying Synthetic Data using Decision Trees

This repository contains code for classifying a synthetic dataset using Decision Trees. The dataset consists of 1500 cases created for a binary classification task, with Class 0 having a uniform distribution and Class 1 constructed using three Gaussian distributions. The main objective is to demonstrate how to categorize examples using a Decision Tree classifier.

 Creation of Datasets

The dataset is generated in Python using Matplotlib and NumPy libraries. For Class 1, three Gaussian distributions are employed, with means of [6,14], [10,6], and [14,14]. Class 0 is formed with a uniform distribution over the range [0, 20].

 Classification with Decision Trees

The scikit-learn package is utilized to create a Decision Tree classifier. The dataset is split into training and testing sets, and the classifier is trained on the training set. Subsequently, the accuracy of the classifier is evaluated using the test set.

 Acknowledgements

- This code was written as part of a machine learning exercise.
  
