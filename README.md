# image-classification-project
This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset into one of 10 categories. The goal is to build, train, and evaluate a deep learning model capable of accurately identifying images of airplanes, cars, animals, and more.

## Dataset
The project uses the **CIFAR-10 datset**, which contains:
- 60,000 32x32 color images in 10 classes
- 50,000 training images and 10,000 test images
- Classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

## Features
- Data preprocessing and normalization
- One-hot encoding of labels
- CNN architecture with convolutional, pooling, and dense layers
- Early stopping during training to prevent overfitting
- Visualization of predictions with correct/incorrect labels
- Model evaluation on test data
- Saving the trained model

## Tools / Libraries
- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn
