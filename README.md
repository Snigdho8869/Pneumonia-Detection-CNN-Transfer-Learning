# Pneumonia Detection using CNN and Transfer Learning with Inceptionv3

This repository contains code for Pneumonia detection from chest X-Ray images using Convolutional Neural Networks (CNNs) with the InceptionV3 architecture. The project is developed using Python, TensorFlow, and Keras.


The code in this repository provides a framework for building a Pneumonia detection system using CNN and InceptionV3 architecture. It includes data preprocessing, model definition, fine-tuning, training, validation, evaluation, and prediction. The dataset used in this project can be downloaded from Kaggle, and it includes chest X-Ray images with Pneumonia (Virus, Bacteria) and Normal labels.

The objective of this project is to detect pneumonia from chest X-ray images.

# Dataset:

This project uses two different datasets.

The reason for using two different datasets is that the CNN model performs better with a smaller dataset, while the Inceptionv3 model requires a larger dataset to achieve better accuracy.

# Transfer Learning:

Transfer Learning is a machine learning technique where a pre-trained model is used as a starting point for a new task. In this project, Inceptionv3 was used as the pre-trained model and retrained on the dataset to detect pneumonia.

# Results:

CNN model achieved an accuracy of 96.2% on the Chest X-Ray Images (Pneumonia) dataset.


Inceptionv3 model achieved an accuracy of 87.49% on the Chest X-Ray Images (Pneumonia) dataset.

# Conclusion:

Pneumonia is a serious medical condition that can be diagnosed using chest X-ray images. In this solo project, I developed CNN and Inceptionv3 models to detect pneumonia from chest X-ray images. I achieved high accuracy with both models, and the CNN model outperformed the Inceptionv3 model. This project demonstrates the effectiveness of transfer learning in medical image analysis.
