# CSC413 Assignment 1: Word Embeddings

## Overview
This assignment focuses on building and analyzing neural networks that predict the next word in a sentence based on the previous three. You will implement this using both **NumPy** and **PyTorch**, applying backpropagation for training. The assignment also explores word embeddings and their representations in vector space.

## Structure
1. **Data Exploration**
   - Analyze sentence structure and word distribution in the dataset.
   
2. **Background Math**
   - Derive gradient descent update rules and computation graphs for a neural network.

3. **Neural Network in NumPy**
   - Implement a multi-layer perceptron (MLP) model from scratch using NumPy, including manual backpropagation.

4. **Neural Network in PyTorch**
   - Implement the same MLP model in PyTorch, leveraging automatic differentiation.

5. **Analyzing Word Embeddings**
   - Explore the learned word embeddings using visualization techniques like **t-SNE**.

## Tasks
- **Data Exploration**: Understand and process the text dataset, including word representations.
- **Math Derivation**: Compute gradients and update rules for training the neural network.
- **Model Implementation**:
  - NumPy: Build and train the model, manually handling forward and backward passes.
  - PyTorch: Build and train the model using PyTorch’s layers and autograd capabilities.
- **Word Embedding Analysis**: Visualize and interpret word embeddings using cosine similarity and t-SNE.

## Requirements
- **NumPy**
- **PyTorch**
- **Matplotlib**
- **Scikit-learn**