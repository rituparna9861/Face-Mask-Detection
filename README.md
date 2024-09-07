# Face-Mask-Detection
This project demonstrates a deep learning-based approach to detect whether people are wearing face masks using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

## Project Overview

With the COVID-19 pandemic, wearing face masks has become essential in public spaces. This project uses computer vision to detect whether a person is wearing a mask or not. The model is trained on a dataset of images of people with and without masks.

## Project Architecture

![Model Architecture](images/model_architecture.png)

The model consists of several convolutional layers followed by pooling layers, activation functions, and fully connected layers. It outputs a binary classification indicating if a mask is present or absent.

## Dataset

The dataset contains two classes:
- `with_mask`: Images of people wearing masks.
- `without_mask`: Images of people not wearing masks.

You can download the dataset [here](https://www.kaggle.com/omkargurav/face-mask-dataset).
