🐱 Cat Classifier with Logistic Regression and Neural Networks

This project is a simple image classification model built using logistic regression implemented with neural networks. The goal is to determine whether an image contains a cat or not.

📌 Description

As part of a lab assignment, this notebook walks through the end-to-end development of a binary classifier using basic deep learning principles. You'll load and preprocess image data, build a neural network from scratch (without high-level frameworks like TensorFlow or PyTorch), and evaluate the model's performance.

🚀 Features

Dataset loading from .h5 files

Image normalization and flattening

Model training using forward and backward propagation

Cost function and gradient descent implementation

Accuracy testing on both training and test sets

Optional: Try your own image for prediction

🧠 Technologies Used

Python

NumPy

Matplotlib

h5py

PIL / SciPy

📂 Dataset
The dataset consists of images labeled as "cat" or "non-cat", stored in HDF5 format (train_catvnoncat.h5 and test_catvnoncat.h5).
