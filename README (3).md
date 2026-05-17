# Part 2 - Computer Vision (CNN Model)

## Project Title
Computer Vision Problem Formulation and CNN Prototype

---

## Project Overview
In this project, a simple Convolutional Neural Network (CNN) model is built to classify images into different categories. The dataset contains images along with their corresponding labels, which are used to train the model.

---

## Dataset Information
The dataset contains a CSV file with the following columns:
- filename: path of the image file
- class: label of the image

The images are organized into different categories.

---

## Problem Statement
This is an image classification problem where the goal is to predict the correct class of an image based on its visual features.

---

## Data Preprocessing
The following preprocessing steps were performed:
- Images were loaded using OpenCV
- Images were resized to 128x128
- Pixel values were normalized (0–1 range)
- Labels were encoded into numeric form
- Dataset was split into training and testing sets (80-20 split)

---

## Model Architecture
A CNN model was built using the following layers:
- Convolution layers for feature extraction
- ReLU activation for non-linearity
- MaxPooling layers for dimensionality reduction
- Flatten layer
- Fully connected Dense layers
- Softmax output layer for classification

---

## Training Details
- Optimizer: Adam  
- Loss Function: Categorical Crossentropy  
- Epochs: 10  
- Batch Size: 32  

---

## Model Evaluation
The model was evaluated using:
- Training and validation accuracy
- Confusion matrix
- Sample predictions on test images

---

## Results
The model was able to learn patterns from the image data and achieved decent performance on the classification task.

---

## CNN Concepts Explained
- Convolution: Extracts important features like edges and patterns from images  
- Pooling: Reduces image size while preserving important information  
- ReLU: Adds non-linearity to improve learning ability of the model  

---

## Real-World Applications
CNN models are widely used in:
- Medical image analysis (X-rays, MRI scans)
- Face recognition systems
- Object detection
- Agriculture (plant disease detection)

---

## Folder Structure
part-2-cnn-computer-vision/
│
├── dataset/
├── results/
├── sample_predictions/
├── notebook.ipynb
├── README.md
└── requirements.txt