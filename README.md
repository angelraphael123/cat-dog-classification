# cat-dog-classification

This project builds a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images of cats and dogs. The model is trained on a labeled dataset and achieves around 74% accuracy on a test set.

---

## Project Overview

- Dataset: Cats and dogs images separated into train, validation, and test sets.
- Model: CNN with multiple convolutional layers, max pooling, dropout, and dense layers.
- Data Augmentation: Applied to training images for better generalization.
- Performance: Model correctly identifies ~74% of test images.
- Tools: TensorFlow 2.x, Keras, Python, Google Colab (recommended for GPU support).

---

## Setup & Usage

### Requirements
- Python 3.x
- TensorFlow 2.x
- matplotlib
- numpy

### Run in Google Colab 
1. Open the notebook in Colab.
2. Run all cells to download the dataset, preprocess images, train the model, and evaluate.

---

## Code Highlights

- Data generators with augmentation to expand training dataset variety.
- CNN architecture with three Conv2D layers, MaxPooling, Dropout, and Dense layers.
- Training for 15 epochs with binary cross-entropy loss and Adam optimizer.
- Visualization of training and validation accuracy and loss over epochs.
- Test predictions with visualization of sample images and confidence scores.

---

## Acknowledgements

- Dataset source: [FreeCodeCamp Cats and Dogs Dataset](https://cdn.freecodecamp.org/project-data/cats-and-dogs/cats_and_dogs.zip)
- TensorFlow tutorials for image classification.

