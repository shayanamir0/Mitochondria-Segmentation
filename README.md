# Mitochondria Segmentation using U-Net

This project focuses on the segmentation of mitochondria in electron microscopy (EM) images using a U-Net architecture. The dataset used is the [EPFL CVLAB Electron Microscopy Dataset](https://www.epfl.ch/labs/cvlab/data/data-em/) (sub-volume).

## Table of Contents
- [Introduction](#introduction)
- [Model Architecture](#model-architecture)
- [Training and Results](#training-and-results)
- [Conclusion](#conclusion)

## Introduction
Accurate segmentation of mitochondria in EM images is crucial for understanding various biological processes. This project utilizes a U-Net model to perform this task, providing a robust solution for automated mitochondria segmentation.

## Model Architecture
The U-Net architecture used in this project is designed for biomedical image segmentation. Below is a high-level overview of the model architecture:

![U-Net Model](https://github.com/user-attachments/assets/5a2c7641-3c13-4529-8e0c-437e0819a087)

The U-Net model consists of an encoder and decoder path. The encoder path captures the context of the input image, while the decoder path enables precise localization. The skip connections between corresponding layers in the encoder and decoder paths help in retaining high-resolution features.

## Training and Results
The model was trained on the EM dataset using appropriate data augmentation techniques to improve generalization. The following metrics were used to evaluate the model performance:

- **Training Accuracy**: 0.984
- **Validation Accuracy**: 0.987

These results indicate a high level of accuracy in segmenting mitochondria from the EM images.

## Conclusion
This project demonstrates the effectiveness of the U-Net architecture in segmenting mitochondria from EM images. The results show that the model can achieve high accuracy, making it a valuable tool for automated analysis in biological research.
