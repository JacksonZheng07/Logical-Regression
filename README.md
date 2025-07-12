# MNIST Digit Classification using Softmax Regression (NumPy)

## Overview

This project implements a multiclass logistic regression (softmax regression) model from scratch using only NumPy. The model classifies handwritten digit images from the MNIST dataset into one of 10 classes (digits 0-9).

Key features of this implementation include:

- Loading and normalizing the MNIST dataset  
- Implementing the softmax activation function  
- Calculating cross-entropy loss  
- Computing gradients manually with vectorized operations  
- Training using mini-batch stochastic gradient descent (SGD)  
- Tracking and visualizing training loss and accuracy over epochs  

---

## Dataset

The MNIST dataset consists of 70,000 grayscale images of handwritten digits (28x28 pixels). The dataset is split into training and testing subsets, with pixel values normalized to the [0,1] range.

---
