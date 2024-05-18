# Sign Language Detection using LSTM

# Overview

This repository contains code and resources for building a Sign Language Detection model using Long Short-Term Memory (LSTM) networks. The goal is to recognize and classify sign language gestures captured in video sequences.

# Features

Data Collection: Gathered a diverse dataset of sign language gestures using video recordings.
Preprocessing: Extracted frames from videos, resized them, and converted them to grayscale.
Model Architecture: Designed an LSTM-based neural network for sequence modeling.
Training: Trained the model on the preprocessed data.
Evaluation: Evaluated the model’s performance using accuracy and confusion matrices.
Inference: Created an inference pipeline to predict sign language gestures in real-time.

# Requirements
Python 3.7+Libraries: pandas, numpy, OpenCV, TensorFlow/Keras

# Usage

Data Preparation:
Collect sign language videos or use an existing dataset.
Extract frames from videos and preprocess them (resize, convert to grayscale, etc.).
Model Training:
Split the dataset into training and validation sets.
Train the LSTM model using the prepared data.
Tune hyperparameters (e.g., sequence length, hidden units, learning rate).
Model Evaluation:
Evaluate the model’s accuracy on the validation set.
Generate a confusion matrix to analyze class-wise performance.
Inference:
Load the trained model.
Capture video frames (e.g., using a webcam).
Pass frames through the model to predict sign language gestures.
Results
Achieved an accuracy of 96% on the validation set.
Confusion matrix highlights common misclassifications.
Future Work
Explore more complex architectures (e.g., 2D CNN + LSTM).
Collect additional data to improve model robustness.
Deploy the model as a real-time application.
