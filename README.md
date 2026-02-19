🧠 Intel Image Classification using Convolutional Neural Networks (CNN)

📌 Project Overview

This project focuses on building and evaluating a Convolutional Neural Network (CNN) model for multi-class image classification using the Intel Image Classification Dataset 

DL Assignment 1 - CNN (1)

.

The objective is to design a deep learning pipeline that performs accurate classification of natural scene images into six categories: Buildings, Forest, Glacier, Mountain, Sea, and Street.

The project demonstrates hands-on expertise in data preprocessing, CNN architecture design, training optimization, model evaluation, and performance visualization.

📂 Dataset

Dataset: Intel Image Classification Dataset

Total Images: 25,000+

Classes (6):

Buildings

Forest

Glacier

Mountain

Sea

Street

⚙️ Project Workflow
1️⃣ Data Preprocessing

Resized images to 150 × 150

Normalized pixel values for faster convergence

Split dataset into:

Training set

Validation set

Test set

Applied Data Augmentation:

Rotation

Horizontal Flip

Zoom

Width/Height Shift

Ensured improved generalization and reduced overfitting

2️⃣ CNN Model Architecture

The CNN model was built from scratch using TensorFlow/Keras and includes:

✅ Minimum 3 Convolutional Layers

✅ ReLU activation functions

✅ Max Pooling layers

✅ Fully Connected (Dense) layers

✅ Dropout regularization

✅ Softmax output layer for multi-class classification

Training optimization techniques:

Early Stopping

Model Checkpointing

Performance monitoring using loss & accuracy curves

3️⃣ Model Evaluation

The trained model was evaluated on the test dataset using:

📊 Accuracy

📈 Precision, Recall, F1-Score (per class)

🔎 Confusion Matrix

🖼️ Visualization of predictions on random test samples

📊 Results

The model achieved strong classification performance across all six classes, demonstrating effective feature extraction and generalization ability through deep convolutional learning.

Performance was validated through:

Training vs Validation Accuracy Curves

Training vs Validation Loss Curves

Class-wise Evaluation Metrics

🛠️ Tech Stack

Python

TensorFlow / Keras

NumPy

Matplotlib

Scikit-learn

🚀 Key Learnings

Practical implementation of CNN from scratch

Importance of data augmentation in preventing overfitting

Model regularization using Dropout

Performance evaluation using classification metrics

Interpreting model predictions using confusion matrices
