# CIFAR-10 Image Classification using CNN (PyTorch)

## Overview

This project implements a Convolutional Neural Network (CNN) using PyTorch for image classification on the CIFAR-10 dataset.

The model uses data augmentation, dropout regularization, and the Adam optimizer to improve performance and reduce overfitting.

## Dataset

CIFAR-10 consists of 60,000 color images across 10 classes:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

## Technologies Used

* Python
* PyTorch
* TorchVision
* NumPy
* Matplotlib

## Model Architecture

* Conv2D (3 → 32)

* ReLU

* MaxPool2D

* Dropout (0.25)

* Conv2D (32 → 64)

* ReLU

* MaxPool2D

* Dropout (0.25)

* Fully Connected Layers

* Dropout Regularization

* Output Layer (10 Classes)

## Data Augmentation

* Random Horizontal Flip
* Random Rotation
* Color Jitter
* Normalization

## Training Configuration

* Optimizer: Adam
* Loss Function: CrossEntropyLoss
* Epochs: 30
* Batch Size: 100

## Results

**Test Accuracy: 76.12%**

## Installation

```bash
pip install -r requirements.txt
```

## Run

```bash
python cnn1.py
```

## Repository

GitHub: https://github.com/yadavnitesh86/Cnn1

## Author

Yadav Nitesh

Machine Learning Enthusiast | BCA Student
