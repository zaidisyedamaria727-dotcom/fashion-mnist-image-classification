# Fashion-MNIST Clothing Recognition using ANN

## Project Overview
This project uses an Artificial Neural Network (ANN) to recognize and classify clothing images from the Fashion-MNIST dataset.

The model predicts clothing categories such as shirts, trousers, dresses, bags, and ankle boots.

## Project Objective
To build, train, and evaluate a neural network that can classify grayscale fashion images into their respective categories.

## Dataset
- Dataset: Fashion-MNIST
- Total images: 70,000
- Image size: 28 × 28 pixels
- Image type: Grayscale
- Number of classes: 10

## Technologies and Libraries
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Gradio
- Google Colab

## Model Architecture
The project uses an Artificial Neural Network with the following layers:

- Flatten Layer
- Dense Layer (128 neurons) with ReLU activation
- Output Dense Layer with Softmax activation

## Model Training
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Training Epochs: 5

## Model Performance
- Test Accuracy: 87.46%
- Test Loss: 0.3500

## Prediction Example
The trained model can predict clothing categories from sample images. One example prediction was **Ankle Boot**.

## Gradio Interface
A Gradio interface was developed to allow users to upload an image and receive a model prediction.

**Note:** The model was trained on Fashion-MNIST images. Real-world clothing photos may produce inaccurate predictions because their backgrounds, colors, shapes, and image formats can differ from the training dataset.

## How to Run
1. Download or clone this repository.
2. Open the notebook in Google Colab.
3. Run the notebook cells in order.
4. Load the Fashion-MNIST dataset.
5. Train and evaluate the ANN model.
6. Use the Gradio interface for predictions.

## Learning Outcomes
- Understanding Artificial Neural Networks
- Image preprocessing and classification
- Building a neural network with TensorFlow and Keras
- Model training and evaluation
- Creating an interactive interface using Gradio

## Author
BS Computer Science Student | Aspiring AI/ML Engineer
