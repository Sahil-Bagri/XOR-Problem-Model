## *XOR Neural Network Training*

This project demonstrates how a Neural Network can learn the XOR (Exclusive OR) problem, a classic example that cannot be solved using a single linear model. The implementation uses TensorFlow / Keras to train a simple feedforward neural network and visualize both the dataset and the learned decision boundary.

# 📌 Project Overview

The XOR problem is a fundamental concept in machine learning that highlights the importance of hidden layers in neural networks. In this notebook:

A custom XOR dataset is loaded

A neural network with a hidden layer is trained

Model performance is evaluated

Decision boundaries are visualized

🧠 Model Architecture

Input Layer: 2 features (X1, X2)

Hidden Layer:

2 neurons

ReLU activation

Output Layer:

1 neuron

Sigmoid activation

Loss Function: Binary Crossentropy

Optimizer: Adam

## 📂 Dataset

The dataset (Xor_Dataset.csv) contains three columns:

Column	Description
X1	First input feature
Y	Second input feature
Z	XOR output label (0 or 1)


X	Y	Z
0	0	0
0	1	1
1	0	1
1	1	0

## 📊 Visualizations

The notebook includes:

Scatter plot of the XOR dataset

Training loss curve

Decision boundary visualization showing how the neural network separates classes

## 🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

TensorFlow / Keras

## ✅ Key Learning Outcomes

Why XOR cannot be solved with linear models

Importance of hidden layers in neural networks

How neural networks learn non-linear decision boundaries

Visual interpretation of model predictions


## 👤 Author

Sahil Bagri
Aspiring Data Scientist / Machine Learning Enthusiast
