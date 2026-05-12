# Fashion MNIST CNN Assignment

## Student Details
Name: Sneha Sharma  
SRN: PES1PG25CS066  

---

## Project Overview

This project implements a Convolutional Neural Network (CNN) from scratch using NumPy for the Fashion MNIST dataset.

The CNN includes:

- Convolution Layer
- Max Pooling Layer
- Softmax Layer
- Forward Pass
- Backpropagation
- Training Loop
- Evaluation Metrics

The project demonstrates the internal working of CNNs without using high-level deep learning libraries like TensorFlow or PyTorch for CNN layers.

---

## Dataset

Fashion MNIST dataset contains:

- 60,000 training images
- 10,000 testing images
- 10 fashion categories
- Image size: 28x28 grayscale

---

## CNN Architecture

Input Image (28x28)
↓
Convolution Layer (3x3 filters)
↓
Max Pooling Layer
↓
Flatten Layer
↓
Softmax Layer
↓
Classification Output

---

## Features Implemented

- Manual convolution operation
- Manual max pooling
- Forward propagation
- Backward propagation
- Weight updates using gradient descent
- Loss calculation
- Accuracy calculation
- Graph visualization
- Prediction visualization

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- Google Colab

---

## How to Run

1. Open the notebook in Google Colab
2. Run all cells sequentially
3. Training will begin automatically
4. Graphs and predictions will be displayed

---

## Output

The notebook displays:

- Training loss graph
- Training accuracy graph
- Final test accuracy
- Sample predictions

---

## Conclusion

This project successfully demonstrates the implementation of a basic CNN from scratch and shows how convolutional neural networks learn image features for classification tasks.
