# LeNet-Inspired CNN for Image Classification
## 📘 Project Overview
This project implements a LeNet-inspired Convolutional Neural Network (CNN) using PyTorch for classifying bioimage data. CNNs are a powerful type of neural network architecture commonly used in image recognition and classification tasks due to their ability to learn hierarchical features through convolutional operations.

The network is loosely based on the classical LeNet architecture, extended with three convolutional layers, three max pooling layers, and two fully connected layers to classify microscopy images from the BBBC021v1 dataset.

## 🧬 Dataset
The dataset used in this project is a subset of the BBBC021v1 MoA dataset:

📚 Source: Broad Bioimage Benchmark Collection

🧪 Original study: Mechanism of Action dataset

🧵 Subset: Only the six main mechanisms of action (MoAs) are selected for faster and more efficient model training.

This dataset contains microscopy images of human cells treated with different compounds, with corresponding labels indicating the MoA of the treatment.

## 🏗️ Model Architecture
The LeNet-inspired architecture used in this project includes:

🧩 3 Convolutional Layers to extract spatial features

🌀 3 Max Pooling Layers to reduce dimensionality

🔗 2 Fully Connected Layers to perform classification

The network gradually learns more complex features—starting from edges and textures in the early layers to cell-level features in the deeper layers.
