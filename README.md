# 🌸 Flower Classification AI

A deep learning project that classifies flower images into five different categories using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

## 📌 Project Overview

The objective of this project is to develop an image classification model capable of recognizing different types of flowers from images.

The model was trained using a dataset containing **3,670 flower images** belonging to five classes:

- 🌼 Daisy
- 🌻 Dandelion
- 🌹 Roses
- 🌻 Sunflowers
- 🌷 Tulips

## 🧠 Machine Learning Approach

The project follows an end-to-end deep learning workflow:

1. Dataset collection and preparation
2. Image resizing and normalization
3. Training and validation dataset creation
4. Convolutional Neural Network development
5. Model training
6. Data augmentation
7. Dropout for reducing overfitting
8. Model evaluation
9. Prediction on new images
10. TensorFlow Lite conversion

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab
- TensorFlow Lite

## 🧠 Model Architecture

The CNN contains:

- Convolutional layers
- Max pooling layers
- Flatten layer
- Dense layers
- ReLU activation
- Dropout regularization
- Softmax-based prediction

## 📊 Dataset

The dataset contains:

**3,670 images across 5 flower classes**

The data was divided into:

- **80% training data**
- **20% validation data**

Images were resized to:

**180 × 180 pixels**

## 🔄 Data Augmentation

Data augmentation was used to create variations of training images and help the model generalize better.

Techniques included:

- Random horizontal flipping
- Random rotation
- Random zoom

## 🤖 Prediction

The trained model was tested using new flower images that were not part of the training process.

One of my tests correctly identified an uploaded image as:

**🌷 Tulips — 77.86% confidence**

## 📱 TensorFlow Lite

The trained Keras model was converted into **TensorFlow Lite (`.tflite`) format**.

This allows the model to be used in lightweight and resource-constrained environments such as mobile and edge devices.

## 📸 Project Screenshots

### Training & Validation Results

![Training Results](training-results.png)

### Data Augmentation

![Data Augmentation](data-augmentation.png)

### Flower Prediction

![Prediction Result](prediction-result.png)

## 🚀 How to Run

### 1. Open the notebook

Open:

`classification.ipynb`

using Google Colab or Jupyter Notebook.

### 2. Install the required libraries

```bash
pip install tensorflow numpy matplotlib pillow
