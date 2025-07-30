# Image-Classification-on-MNIST-using-ANN

## Overview
This repository contains a beginner-friendly implementation of an Artificial Neural Network (ANN) to classify handwritten digits from the MNIST dataset. The model is built using TensorFlow and Keras, trained on grayscale images of digits ranging from 0 to 9.

## Dataset
The MNIST dataset consists of:
- 60,000 training images
- 10,000 test images
- Each image is 28x28 pixels in grayscale.

## Features

- Data preprocessing and normalization
- ANN model building using Keras Sequential API
- Model training and validation
- Evaluation using accuracy and loss plots
- Final testing on unseen data

  ## Model Architecture
  
- Input Layer: 784 neurons (28x28 pixels flattened)
- **Hidden Layers**:
  - Dense(128), activation='relu'
  - Dropout(0.2)
  - Output Layer: Dense(10), activation='softmax'

## Results

- Achieved ~97% test accuracy after training for a few epochs.

## Files

image-classification-on-mnist-dataset-ann.ipynb: Jupyter Notebook with complete code and visualizations.
README.md: Project overview and instructions (this file).
reqirement.txt: dependencies

## How to Run

Open the notebook in Jupyter or run using VSCode:
<code>jupyter notebook image-classification-on-mnist-dataset-ann.ipynb
</code>

## Author
Atishay Jain
