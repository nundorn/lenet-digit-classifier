# Digit Recognizer (Keras + LeNet-5 + Deep Learning)

This project solves the [Kaggle Digit Recognizer](https://www.kaggle.com/competitions/digit-recognizer) challenge using a classic deep learning approach with the LeNet-5 Convolutional Neural Network (CNN) architecture implemented in Keras.

The goal is to classify images of handwritten digits (0–9) from the MNIST-like dataset into their correct numeric labels.

## Features

- Input preprocessing with normalization and reshaping
- CNN model based on the original LeNet-5 architecture
- Built using Keras Sequential API for simplicity
- Activation functions: `tanh` and `softmax` as in the original paper
- Includes dropout layer for basic regularization (optional)
- Validation split used for model performance monitoring
- Generates a submission-ready CSV file for Kaggle evaluation
