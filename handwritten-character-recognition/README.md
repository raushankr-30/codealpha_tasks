# Handwritten Character Recognition System

This project is a deep learning-based system that recognizes handwritten English alphabets (A–Z) using Convolutional Neural Networks (CNN). It leverages the EMNIST Letters dataset and is built using TensorFlow and Keras.

## About

Handwritten character recognition is a fundamental task in computer vision with applications in OCR (Optical Character Recognition), document digitization, postal code reading, and form processing. This project demonstrates how to build a character recognition system using CNNs trained on the EMNIST Letters dataset. The model takes a 28x28 grayscale image of a handwritten character and predicts the corresponding letter (A to Z).

---

## Model Architecture

The model is a Convolutional Neural Network with the following layers:

- Input: 28x28 grayscale image
- Conv2D (32 filters, 3x3 kernel, ReLU activation)
- MaxPooling2D (2x2 pool size)
- Conv2D (64 filters, 3x3 kernel, ReLU activation)
- MaxPooling2D (2x2 pool size)
- Flatten layer
- Dense layer (128 units, ReLU activation)
- Dropout layer (rate: 0.3)
- Output Dense layer (26 units, softmax activation)

Loss Function: `categorical_crossentropy`  
Optimizer: `adam`  
Evaluation Metric: `accuracy`

### Install Required Packages

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
