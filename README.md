# Handwritten Digit Classification

This project implements a neural network to classify handwritten digits using the [MNIST dataset](http://yann.lecun.com/exdb/mnist/). The model is built and trained using TensorFlow and Keras, and demonstrates the ability of Artificial Neural Networks (ANNs) to solve image classification problems effectively.

---

## Features
- Uses the **MNIST dataset** of handwritten digits.
- Implements a **Feedforward Neural Network** with:
  - Input layer matching the pixel size of the images.
  - Hidden layers with ReLU activation.
  - Output layer for multi-class classification with Softmax activation.
- Trained with **Adam Optimizer** and **Categorical Crossentropy** loss.
- Achieves high accuracy on the test set.

---

## Project Structure
- `handwritten_digits_classification.ipynb`: Jupyter Notebook containing the implementation, including:
  - Data preprocessing.
  - ANN model building and training.
  - Evaluation and visualization of results.
- Example outputs: Displays prediction results with their respective images.

---

## Setup and Requirements

### Dependencies
- Python 3.7+
- TensorFlow
- NumPy
- Matplotlib

Install the dependencies using:
```bash
pip install tensorflow numpy matplotlib
