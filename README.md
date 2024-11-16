# Deep Neural Network for Breast Cancer Classification

## Overview
This project demonstrates how to build and train a deep neural network for classifying breast cancer cells into two classes: benign and malignant. The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Data Set, a widely used dataset in machine learning for classification tasks. The neural network is built and trained using PyTorch, and several optimizations and model evaluations are performed.

## Objectives
- Use PyTorch to build and train a deep neural network for classification.
- Preprocess the dataset, including splitting the data, separating features and labels, and standardizing feature values.
- Experiment with different optimizers, such as Stochastic Gradient Descent (SGD), and observe how they affect the model's performance.
- Visualize the training and test loss over time to monitor the model's learning progress.

## Background
### What is PyTorch?
PyTorch is an open-source machine learning library developed by Facebook's AI Research lab (FAIR). It is widely used in deep learning applications, especially for tasks related to computer vision and natural language processing. PyTorch facilitates building, training, and deploying deep learning models with a focus on flexibility and speed.

### Common Uses of PyTorch:
- Developing deep learning models (e.g., CNNs, RNNs).
- Rapid prototyping for research and experimentation.
- Transitioning models from research to production with tools like TorchServe.

## Setup
To run this project, you will need to install the following libraries:
- `pandas` for data management.
- `numpy` for mathematical operations.
- `matplotlib` for plotting and visualizations.
- `sklearn` for machine learning utilities.
- `torch` for building and training the neural network.
- `ucimlrepo` for loading the dataset.

You can install the required libraries by running the following command:

```bash
pip install pandas numpy matplotlib scikit-learn torch ucimlrepo
