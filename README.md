# Brain-Tumor-classification
🔍 Project Overview

The Brain Tumor Classification project focuses on detecting and classifying brain tumors from MRI scans using Deep Learning with PyTorch. The goal was to build a model that can assist in medical image analysis, improving diagnosis accuracy and speed.

⚙️ Steps I Followed

Dataset Preparation

Collected MRI scan images categorized into tumor and non-tumor classes.

Performed preprocessing such as resizing, normalization, and data augmentation (rotation, flipping) to improve model generalization.

Model Building

Implemented a Convolutional Neural Network (CNN) architecture using PyTorch.

Designed layers with convolution, pooling, batch normalization, and dropout for robust feature extraction.

Applied softmax output for classification.

Training & Evaluation

Used CrossEntropy Loss and Adam optimizer.

Applied early stopping and learning rate scheduling for stable training.

Evaluated with accuracy, precision, recall, and F1-score.

Plotted confusion matrix to visualize classification performance.

Results

Achieved strong accuracy in classifying MRI images.

Demonstrated potential use of DL in real-world medical applications.
