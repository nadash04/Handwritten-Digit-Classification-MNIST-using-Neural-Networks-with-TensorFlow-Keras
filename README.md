# Handwritten-Digit-Classification-MNIST-using-Neural-Networks-with-TensorFlow-Keras

How it Works
Loads the MNIST dataset (handwritten digits 28×28).
Preprocesses the data by normalizing pixel values and flattening images into vectors of size 784.
Builds a neural network model:
  .Dense layer with 128 neurons (ReLU).
  .Dense layer with 64 neurons (ReLU).
  .Output layer with 10 neurons (Softmax).
rains the model using Adam optimizer and Sparse Categorical Crossentropy loss.
Evaluates performance on test data.
Plots accuracy and loss curves for training and validation.
Shows predictions on sample test images with their true labels.

Requirements
Make sure you have the following installed:
pip install tensorflow matplotlib numpy

How to Run

Clone this repository:
git clone https://github.com/YourUsername/YourRepoName.git
Run all cells to train the model and see results.

Results

Achieves around 97–98% accuracy on the MNIST test dataset.
Visualization of training vs validation accuracy/loss.
Example predictions on test images with actual vs predicted labels.

Features

End-to-end deep learning workflow.
Data preprocessing, training, evaluation, and visualization.
Simple, beginner-friendly neural network model.
