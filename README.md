# Image_Classification

This project demonstrates image classification on the COIL-100 dataset using a custom Convolutional Neural Network (CNN) built with PyTorch.
Table of Contents

## Project Overview
- Dataset
- Installation
- Usage
- Model Architecture
- Results

## Project Overview

The goal of this project is to classify images from the COIL-100 dataset into one of 100 categories representing different objects. The project includes:

Loading and preprocessing the dataset.

Building a CNN model for classification.

Training and evaluating the model.

## Dataset

The COIL-100 dataset contains 100 objects with 72 images per object taken from different angles. Each image is 128x128 pixels. The dataset is freely available at COIL-100 Dataset.

## Data Structure

Images are named as obj1__0.png, where 1 is the object label.


## Model Architecture

The CNN model includes:

3 Convolutional layers with ReLU activation and MaxPooling.

Batch normalization layers for faster convergence.

Fully connected layers for classification.

## Results

Validation Accuracy: ~84%




Contributions are welcome! Please fork this repository and submit a pull request.

