# CIFAR-10 CNN Image Classification

This project implements a Convolutional Neural Network (CNN) from scratch using PyTorch to classify images from the CIFAR-10 dataset.

The model learns to identify patterns like edges, shapes, and textures through 3 convolutional layers and classifies each image into one of 10 categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

## Model Architecture
- Conv2D(3 -> 32) + ReLU + MaxPool
- Conv2D(32 -> 64) + ReLU + MaxPool
- Conv2D(64 -> 128) + ReLU + MaxPool
- Fully Connected: 4*4*128 -> 256 -> 10

## Results
- **Test Accuracy: 76.71%**
- Epochs: 10
- Optimizer: Adam
- Loss: CrossEntropyLoss

## Tech Stack
Python, PyTorch, Torchvision, NumPy, Matplotlib

## How to Run
pip install torch torchvision
jupyter notebook cifar10_cnn.ipynb
