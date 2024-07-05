# GNN Classification of MNIST Images

## Project Overview

This project focuses on training a Graph Neural Network (GNN) model for the classification of MNIST images, based on the methodology described in the paper ["Graph Neural Networks for Image Classification"](https://iopscience.iop.org/article/10.1088/1742-6596/1871/1/012071/pdf). The architecture has been modified to include 4 GATConv layers and 3 fully connected (Fc) layers. The project also involves hyperparameter tuning, visualization of images in graph format, and a comparison of the GNN's performance with a typical Convolutional Neural Network (CNN).

## Features

- **GNN Model Architecture**: Includes 4 GATConv layers and 3 Fc layers.
- **Hyperparameter Tuning**: Two sets of hyperparameter tuning logs are provided.
- **Visualization**: MNIST images are visualized in graph format for all classes.
- **Performance Comparison**: Accuracy and training time compared with a typical CNN.

## Requirements

The project requires the following Python packages:

```plaintext
torch
torchvision
torch-geometric
numpy
matplotlib
scikit-learn
