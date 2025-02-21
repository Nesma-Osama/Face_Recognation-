# Face Recognition Using CNN, HOG + PCA, and ML Models

## Overview

This project implements face recognition using two different approaches:

1-Deep Learning Approach: A Convolutional Neural Network (CNN) trained on a Kaggle dataset.

2-Traditional Machine Learning Approach: Using Histogram of Oriented Gradients (HOG), Principal Component Analysis (PCA), and classification models like K-Nearest Neighbors (KNN) and Support Vector Classifier (SVC).

Additionally, the CNN model has been tested using video-based face detection with Haar Cascade classifiers.

## Dataset

Collected and modified a face dataset from Kaggle, featuring images of 10 well-known actors.

Dataset available at:https://drive.google.com/file/d/1IxIM_4qsiUQv7YKpcPnmgfcLa8sxw87d/view?usp=drive_link.

### Actors

Charlize Theron

Elizabeth Olsen

Henry Cavill

Priyanka Chopra

Tom Cruise

Chris Evans

Chris Hemsworth

Mark Ruffalo

Robert Downey Jr.

Scarlett Johansson

## Implementation Details

### 1. CNN-Based Face Recognition

Uses a deep learning model to classify faces.

Trained on labeled images of the 10 actors.

Tested on real-time video input using Haar Cascade for face detection.

Achieved 82% accuracy.

### 2. HOG + PCA + ML-Based Face Recognition

Extracts facial features using Histogram of Oriented Gradients (HOG).

Reduces dimensionality using Principal Component Analysis (PCA).

Classifies using:

Support Vector Classifier (SVC) – 90% accuracy

K-Nearest Neighbors (KNN) – 78% accuracy

Results and Performance Compariso

