# Deep Learning

My deep learning learning journey and practice projects.

This repository contains small models and experiments that I build while learning Deep Learning concepts through coursework and practice.

## Projects

### 1. Plant Watering Prediction Using Artificial Neural Network (ANN)

A beginner-level binary classification project that predicts whether a plant needs water based on soil moisture, temperature, and sunlight hours.

**Technologies Used**
- Python
- NumPy
- Pandas
- TensorFlow / Keras

**Concepts Learned**
- Data preprocessing
- Min-Max scaling
- Training and testing data split
- Artificial Neural Networks
- Dense layers
- Binary cross-entropy loss
- Stochastic Gradient Descent (SGD)
- Model training and validation

**Model Architecture**

Input Layer (3 features) → Hidden Layer (8 neurons, ReLU) → Output Layer (1 neuron, Sigmoid)

**Dataset**

A small, manually created dataset containing 16 observations. It is used for educational purposes only.

**Limitations**

The dataset is too small to build a reliable real-world plant-watering prediction system.

---

### 2. Iris Flower Classification Using Perceptron and ANN

A multiclass classification project using the Iris dataset to classify flowers into three species based on their sepal and petal measurements.

**Technologies Used**
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

**Concepts Learned**
- Exploratory Data Analysis (EDA)
- Data visualization using pair plots
- Label encoding
- Training and testing data split
- Feature standardization
- Perceptron classification
- Artificial Neural Networks
- Softmax activation
- Model evaluation using accuracy, precision, recall, and F1-score
- Training and validation accuracy visualization

**Model Architecture**

Input Layer (4 features) → Hidden Layer (16 neurons, ReLU) → Hidden Layer (8 neurons, ReLU) → Output Layer (3 neurons, Softmax)

**Results**
- Perceptron accuracy: 86.67%
- ANN test accuracy: approximately 93.33%

**Dataset**

The Iris dataset contains 150 observations, four numerical features, and three flower species.

---

## Learning Goals

- Understand neural network fundamentals.
- Practice implementing deep learning models.
- Experiment with different activation functions and architectures.
- Learn data preprocessing and model evaluation techniques.
- Build a foundation for future Machine Learning and AI research.

# MNIST Handwritten Digit Classification

## Overview
This project implements and compares three neural network models for handwritten digit classification using the MNIST dataset.

## Models
- Perceptron
- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)

## Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- TensorFlow / Keras
- Scikit-learn
- Google Colab

## Experiments
- Data preprocessing and normalization
- Model training and testing
- Final test accuracy comparison
- Training and validation accuracy/loss visualization
- Prediction comparison across models

## Evaluation
The models are evaluated using test accuracy to compare their classification performance.

## How to Run
Open `mnist_cnn_classification.ipynb` in Google Colab and run the notebook cells in order.

## Dataset
MNIST handwritten digit dataset.

More projects will be added as I continue learning.

*This repository is a work in progress.*
