# Image Classification using CNN vs. DenseNet on CIFAR-10

![Image Classification](https://img.shields.io/badge/Image%20Classification-CNN%20vs.%20DenseNet-brightgreen.svg)
![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange.svg)

A Deep Learning project for image classification on the CIFAR-10 dataset. This project compares the performance of Convolutional Neural Networks (CNN) and DenseNet architectures to determine which one is more effective for classifying a diverse set of images.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Model Architectures](#model-architectures)


## Introduction
The Image Classification project focuses on classifying images into ten distinct classes using deep learning techniques. It compares two different neural network architectures, Convolutional Neural Networks (CNN) and DenseNet, to assess their effectiveness in image classification tasks.

## Features
- Input features consist of RGB images from the CIFAR-10 dataset.
- Utilizes two deep learning architectures: CNN and DenseNet.
- Provides performance metrics and comparative results to determine the superior model.

## DataSet

The dataset used in this project is the **CIFAR-10 dataset**, a popular and challenging dataset for image classification tasks. Here are some important details about the dataset:

### Dataset Overview

- **NTumber of Samples:** The CIFAR-10 dataset consists of a total of 60,000 images.
  - **Training Set:** 50,000 images
  - **Test Set:** 10,000 images
  - 
**Classes:** It is a multi-class classification problem, where each image belongs to one of the ten distinct classes. The classes in CIFAR-10 are as follows:
  1. Airplane
  2. Automobile
  3. Bird
  4. Cat
  5. Deer
  6. Dog
  7. Frog
  8. Horse
  9. Ship
  10. Truck
- **Image Dimensions:** All images in the dataset are 32x32 pixels in size, making them relatively small compared to some other image datasets.

- **Color Channels:** Images in CIFAR-10 are in RGB (Red, Green, Blue) format, providing color information for each pixel.

## Model Architectures
I have used CNN and DenseNet for this image classification project, the detailed architecture is given inside the python notebook 
