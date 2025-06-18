# FashionMNIST Classification with PyTorch

This repository contains a PyTorch implementation of a Convolutional Neural Network (CNN) with Residual Blocks for classifying images from the FashionMNIST dataset.

---

## Features

- Loads and preprocesses FashionMNIST dataset with resizing and tensor conversion.
- Visualizes random samples from the training data.
- Defines a custom Residual Block module.
- Builds a deep CNN model using Residual Blocks and adaptive average pooling.
- Trains the model with cross-entropy loss and Adam optimizer.
- Evaluates model performance on the test set using accuracy from scikit-learn.

---

## Requirements

- Python 3.7+
- PyTorch
- torchvision
- scikit-learn
- matplotlib
