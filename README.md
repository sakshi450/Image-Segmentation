# Image-Segmentation
# Retinal Blood Vessel Segmentation using U-Net
This repository contains the implementation of a Retinal Blood Vessel Segmentation model using the U-Net architecture. The project utilizes the DRIVE dataset, a widely used dataset for retinal vessel segmentation tasks.

# Table of Contents
Introduction
Dataset
Model Architecture
Installation
Usage
Results
Acknowledgments
License
Introduction
Retinal blood vessel segmentation is crucial for the diagnosis and treatment of various ophthalmic conditions such as diabetic retinopathy and glaucoma. This project implements a U-Net-based deep learning model to perform accurate segmentation of blood vessels in retinal images.

# Dataset
We use the DRIVE dataset (Digital Retinal Images for Vessel Extraction), which consists of 40 images divided into training and test sets. Each image has a corresponding ground truth annotation.

Training set: 20 images
Test set: 20 images
The dataset can be downloaded from the official DRIVE website.

# Model Architecture
The model is based on the U-Net architecture, a popular convolutional neural network for biomedical image segmentation. The U-Net consists of:

Encoder: A series of convolutional and max-pooling layers that capture high-level features.
Decoder: Upsampling layers that help in reconstructing the image with the segmentation mask.
Skip Connections: To combine high-resolution features from the encoder with upsampled features in the decoder, ensuring better localization.


# Installation
Prerequisites
Ensure you have Python 3.7+ installed along with the following libraries:

TensorFlow / PyTorch (choose one based on your preference)
NumPy
OpenCV
Matplotlib
Scikit-learn
