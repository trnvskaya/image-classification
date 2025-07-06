# Machine Learning Projects

These notebooks were developed as part of the *Machine Learning 2* course at the Faculty of Information Technology, Czech Technical University in Prague (FIT ČVUT).

This repository contains two projects:

## **1. Image Classification & Dimensionality Reduction**

**Description:**
In this project, we explore multiple models for classifying the same image dataset. We compare SVM, Naive Bayes, and LDA classifiers, tune hyperparameters, test normalization methods, and apply dimensionality reduction techniques (PCA and LLE) to improve performance.

**Key Steps:**

* Data splitting for training and testing
* Model training with hyperparameter tuning (including different SVM kernels)
* Experiment with data normalization
* Apply PCA and LLE to find optimal dimensions
* Compare results and estimate final model performance on unseen images



## **2. Neural Network Image Classification**

**Description:**
In this project, we build a neural network in PyTorch to classify images from the same dataset. We preprocess and normalize the data, split it into training, validation, and test sets, and train the network to predict image labels. We also evaluate its performance and discuss the results.
**Key Steps:**

* Load and normalize image data for training
* Split data into training, validation, and test sets
* Build and train a neural network using PyTorch
* Evaluate model accuracy on unseen data
