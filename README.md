# Handwritten Digit Recognition
This project involves building an Artificial Neural Network (ANN) model to recognize handwritten digits from the MNIST dataset. The model is trained to classify digits from 0 to 9.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Requirements](#requirements)

## Introduction

Handwritten digit recognition is a classic problem in the field of machine learning and computer vision. This project uses an ANN to classify digits from the MNIST dataset, which contains 70,000 grayscale images of handwritten digits.

## Dataset

The MNIST dataset includes:
- 60,000 training images
- 10,000 test images

Each image is a 28x28 pixel grayscale image representing a handwritten digit.

## Model Architecture

The ANN model consists of the following layers:
1. Input Layer: Takes in 784 features (28x28 pixels flattened).
2. Hidden Layer 1: Fully connected layer with 128 neurons and ReLU activation.
3. Hidden Layer 2: Fully connected layer with 32 neurons and ReLU activation.
4. Output Layer: 10 neurons with softmax activation to classify digits from 0 to 9.

## Requirements

To run this project, you will need the following packages:
- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib
