# Titanic Survival Prediction

This project demonstrates a machine learning pipeline for predicting Titanic survival rates using TensorFlow and Keras. The dataset is preprocessed, features are encoded, and a neural network model is trained to classify survival outcomes.

## Project Structure

## Features

- **Data Loading**: Reads Titanic dataset from a public URL.
- **Data Preprocessing**:
  - Splits the dataset into training, validation, and test sets.
  - Encodes categorical and numerical features using TensorFlow layers.
- **Model Building**:
  - Constructs a neural network using Keras Functional API.
  - Includes normalization and category encoding layers.
- **Training and Evaluation**:
  - Trains the model using Adagrad optimizer and binary cross-entropy loss.
  - Evaluates the model on a test dataset.

## Requirements

- Python 3.12 or later
- TensorFlow 2.16.2 or later
- Keras
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/omotayosam/titanic-survival.git
   cd titanic-survival
