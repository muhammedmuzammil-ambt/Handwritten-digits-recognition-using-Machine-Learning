# Handwritten Digit Recognition (MNIST, CNN)

A convolutional neural network that classifies handwritten digits (0–9) from the classic MNIST dataset, built with TensorFlow/Keras.

## Overview

This project trains a CNN on the Kaggle "Digit Recognizer" MNIST-style dataset (28×28 grayscale pixel values in CSV form) and generates a submission file with predicted labels for the test set.

## Dataset

- `train.csv` — 42,000 labeled images, 785 columns (`label` + 784 pixel values)
- `test.csv` — 28,000 unlabeled images, 784 pixel columns
- Pixel values normalized from 0–255 to 0–1
- Images reshaped to 28×28×1 for CNN input

Get the dataset from [Kaggle's Digit Recognizer competition](https://www.kaggle.com/competitions/digit-recognizer/data) and place `train.csv` / `test.csv` in the working directory (update the file paths in the notebook if not using Colab's `/content/` path).

## Model Architecture
