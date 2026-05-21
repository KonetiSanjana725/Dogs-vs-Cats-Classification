# Dog vs Cat Image Classification using CNN

## Project Overview

This project focuses on building a **Convolutional Neural Network (CNN)** model to classify images of **dogs and cats** using Deep Learning techniques.
The model is trained using image preprocessing, data augmentation, and data generators to improve performance and generalization.

The project also includes:

* Training and validation accuracy/loss visualization
* Confusion Matrix evaluation
* Testing on custom images

---

## Technologies Used

* **Programming Language:** Python
* **Framework:** TensorFlow / Keras

### Libraries Used

* TensorFlow / Keras
* NumPy
* Matplotlib

---

## Features

* Image preprocessing and normalization
* Data augmentation for better generalization
* CNN-based image classification
* Training and validation performance curves
* Confusion Matrix evaluation
* Prediction on custom images

---

## Dataset

The dataset contains two categories:

* Cats
* Dogs

Images are organized into:

* Training set
* Validation/Test set


## CNN Architecture

The CNN model includes:

* Convolutional Layers
* Max Pooling Layers
* Flatten Layer
* Dense (Fully Connected) Layers
* Output Layer with Sigmoid Activation

---

## Data Preprocessing

The following preprocessing steps were applied:

* Image resizing
* Pixel value normalization
* Batch generation using ImageDataGenerator

---

## Data Augmentation

To reduce overfitting and improve accuracy, data augmentation techniques were used:

* Rescaling
* Rotation
* Zooming
* Horizontal flipping
* Shearing

---

## Model Training

The model was trained using:

* Binary Crossentropy Loss
* Adam Optimizer
* Accuracy Metric

Example training parameters:

* Batch Size: 32
* Epochs: 10

---

## Performance Evaluation

### Validation Curves

The following graphs were plotted:

* Training Accuracy vs Validation Accuracy
* Training Loss vs Validation Loss

These curves help analyze:

* Model performance
* Overfitting/Underfitting

---

## Confusion Matrix

A confusion matrix was used to evaluate classification results.

It shows:

* Correctly classified dogs
* Correctly classified cats
* Incorrect predictions

---

## Sample Results

* Model successfully classifies dog and cat images.
* Achieved good validation accuracy after training.
* Custom image predictions were also tested.

---

## How to Run the Project

### 1. Install Required Libraries

```
pip install tensorflow numpy matplotlib
```

### 2.In Google Colab
Open the notebook in Google Colab
Upload dataset to Google Drive
Mount Google Drive
Run all notebook cells

---

## Future Improvements

* Increase dataset size
* Use Transfer Learning (VGG16, ResNet, MobileNet)
* Hyperparameter tuning
* Deploy as a web application

---

## Learning Outcomes

Through this project, the following concepts were learned:

* CNN architecture
* Image preprocessing
* Data augmentation
* Model evaluation
* Deep Learning with TensorFlow/Keras


