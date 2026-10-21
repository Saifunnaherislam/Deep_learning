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

### 3. MNIST Digit Classification Using Perceptron, ANN and CNN

A handwritten digit classification project that compares the performance of Perceptron, Artificial Neural Network (ANN), and Convolutional Neural Network (CNN) models on the MNIST dataset. The models are trained to classify handwritten digits from 0 to 9 using pixel values as input features.

**Technologies Used**

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- Google Colab

**Concepts Learned**

- Data loading and preprocessing
- Image pixel normalization
- Reshaping image data for neural networks
- Perceptron classification
- Artificial Neural Networks (ANN)
- Convolutional Neural Networks (CNN)
- Convolution and max pooling
- Flattening and dense layers
- Dropout for reducing overfitting
- Model training and testing
- Test accuracy comparison
- Data visualization and model evaluation

**Model Architectures**

- **Perceptron:** A basic classification model using flattened pixel values as input features.
- **ANN:** A neural network that learns patterns from flattened image data using dense layers.
- **CNN:** A convolutional neural network that extracts spatial features from images using convolutional and max-pooling layers, followed by dense layers for digit classification.

**Dataset**

The project uses a handwritten digit dataset containing 28 × 28 pixel images represented by 784 pixel features. The dataset used in this project contains 42,000 observations.

**Training Details**

- Number of Epochs: 5
- Total Training Time: 2 minutes 42 seconds
- Training Environment: Google Colab

The models were trained for 5 epochs, taking approximately 2 minutes and 42 seconds to complete the training process.

**Results**

The test accuracy of Perceptron, ANN, and CNN is evaluated and compared to understand how different neural network architectures perform on handwritten digit classification.

**Learning Outcome**

This project provides practical experience in image classification and demonstrates how CNNs can learn spatial patterns from image data compared with traditional classification and fully connected neural network models.
More projects will be added as I continue learning.

*This repository is a work in progress.*
