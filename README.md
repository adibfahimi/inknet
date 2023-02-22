# Handwritten Digit Recognition Project

This project is an implementation of a handwritten digit recognition system using Python. The project is based on the MNIST dataset, which is a collection of 60,000 training and 10,000 testing images of handwritten digits. The main goal of the project is to create a machine learning model that can accurately classify the digits.

## Project Overview

The handwritten digit recognition system is implemented using a neural network. The neural network is a feedforward neural network with one hidden layer. The input layer of the neural network has 784 nodes, which corresponds to the 28 x 28 pixels of the images in the MNIST dataset. The first hidden layer has 256 nodes and the secend hidden layer has 128 nodes, and the output layer has 10 nodes, each corresponding to one digit from 0 to 9.

The neural network is trained using the backpropagation algorithm with stochastic gradient descent. The cross-entropy loss function is used to calculate the error, and the softmax function is used to calculate the probabilities of the output.

After training the model, the performance is evaluated on the test dataset. The accuracy of the model is reported, and a confusion matrix is generated to visualize the performance of the model.
