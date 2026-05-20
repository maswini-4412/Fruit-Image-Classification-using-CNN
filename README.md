# Fruit-Image-Classification-using-CNN


## Project Overview
This project implements a Convolutional Neural Network (CNN) from scratch for multi-class image classification.  
The model classifies fruit images into five categories:

- Apple Red
- Banana
- Citrus Orange
- Mango
- Strawberry

The project was developed using TensorFlow and Keras without using pretrained models.

---

# Dataset Structure

dataset/

├── train/

│ ├── Apple Red

│ ├── Banana

│ ├── Citrus Orange

│ ├── Mango

│ └── Strawberry

│

└── test/

├── Apple Red

├── Banana

├── Citrus Orange

├── Mango

└── Strawberry


---

# Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

---

# CNN Architecture

The CNN model contains:

1. Convolutional Layers (Conv2D)
2. MaxPooling Layers
3. Flatten Layer
4. Dense Layer
5. Dropout Layer
6. Softmax Output Layer

---

# Image Preprocessing

- Image size: 128x128
- Normalization using ImageDataGenerator
- Batch size: 32

---

# Training Details

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Epochs: 10
- Activation Function: ReLU and Softmax

---

# Evaluation Metrics

The following metrics were used:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

# Final Results

- Test Accuracy: ~98%
- Stable training and validation performance
- Good classification performance on selected fruit classes

---
