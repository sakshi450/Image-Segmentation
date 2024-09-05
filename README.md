# Image-Segmentation
# Retinal Blood Vessel Segmentation using U-Net
This repository contains the implementation of a Retinal Blood Vessel Segmentation model using the U-Net architecture. The project utilizes the DRIVE dataset, a widely used dataset for retinal vessel segmentation tasks.

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

