# Movie Poster Genre Classifier
A multi-label image classifier that predicts movie genres from poster images using deep learning.

## Overview
This model analyzes movie posters and predicts multiple genres simultaneously (Action, Comedy, Drama, etc.) using convolutional neural networks.

## Performance
Label-wise Accuracy: 91.6%
Hamming Loss: 0.084
Model Type: Multi-label CNN classifier

-How to use
from tensorflow.keras.models import load_model

-Load the model
model = load_model('new_model_name.h5')

-Predict genres from poster image
predictions = model.predict(image_array)

## Dataset
An unbalanced dataset of 7868 Images of Movie poster images with corresponding genre labels for training and evaluation.
(70% Training, 15% Validation, 15% Testing)

## Architecture
ResNet-based convolutional neural network fine-tuned for multi-label movie genre classification.
