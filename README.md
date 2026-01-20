# Brain Tumor Detection

A deep learning project using PyTorch to detect brain tumors from MRI scans with 86% accuracy.

## Overview

This project implements a Convolutional Neural Network (CNN) to classify brain MRI scans and predict whether a tumor is present. The model was developed and trained using PyTorch and Torchvision in a Jupyter Notebook environment.

## Model Performance

- **Initial Model**: 6 convolutional layers → **68% accuracy**
- **Improved Model**: Enhanced architecture with batch normalization → **86% accuracy**

The addition of batch normalization significantly improved the model's performance by stabilizing the learning process and reducing internal covariate shift.

## Technologies Used

- **PyTorch**: Deep learning framework for building and training the neural network
- **Torchvision**: For image transformations and data loading utilities
- **Jupyter Notebook**: Interactive development environment

## Model Architecture

The improved model features:
- 6 convolutional layers
- Batch normalization layers (bn1-bn6) for improved training stability
- Enhanced generalization capabilities

## Key Features

- Binary classification (tumor/no tumor)
- Image preprocessing and augmentation using Torchvision
- Batch processing for efficient training
- Significant accuracy improvement through architectural enhancements
