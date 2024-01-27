# Handwriting Recognition with OpenCV, Keras, TensorFlow, and ResNet Architecture

## Project Overview:
This project focuses on developing an Optical Character Recognition (OCR) model using deep learning techniques. Two datasets were utilized for training:

1. **MNIST 0-9 Dataset by LeCun et al.:** A standard dataset consisting of handwritten digits.
2. **Kaggle A-Z Dataset by Sachin Patel:** Based on the NIST Special Database 19, this dataset contains handwritten characters A-Z.

The OCR model was trained using Keras, TensorFlow, and the ResNet (Residual Neural Network) architecture.

## Overview of Libraries and Platforms Used:
1. **OpenCV:** Employed for image pre-processing, which involved enhancing image quality by removing noise and improving contrast between handwritten text and the background.

2. **Keras:** A high-level neural networks API built on TensorFlow. Keras provides pre-built layers that can be easily combined for efficient implementation of neural networks. Written in Python, it simplifies the process of building and experimenting with deep learning models.

3. **TensorFlow:** Used for its ability to handle large datasets and scale models across multiple devices. TensorFlow facilitates the implementation of best practices for data automation, model tracking, performance monitoring, and model retraining.

4. **ResNet Architecture:** Implemented ResNet, known for its use of residual blocks. These blocks enable the model to learn features from images, allowing the creation of deeper networks without encountering issues such as vanishing gradients.

## Dataset Information:
To access the "a_z_handwritten_data.csv" dataset, you can download it from https://www.kaggle.com/datasets/sachinpatel21/az-handwritten-alphabets-in-csv-format and ensure that the CSV file is placed in the project's root directory.

This project aims to showcase the integration of OpenCV, Keras, TensorFlow, and ResNet architecture for efficient handwriting recognition.
