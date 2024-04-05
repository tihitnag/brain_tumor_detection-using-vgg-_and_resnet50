		                                        Brain Tumour Detection Model
Overview

This repository contains the implementation of a deep learning model for detecting brain tumors from MRI images. The model leverages state-of-the-art convolutional neural network architectures including VGG16, InceptionV3, ResNet50, and EfficientNetB4. Through extensive experimentation and data augmentation techniques, the model achieves high accuracy in identifying brain tumors.

Model Architecture

VGG16: A classic convolutional neural network architecture known for its simplicity and effectiveness in image classification tasks.
InceptionV3: A sophisticated architecture designed by Google, which uses inception modules to capture spatial hierarchies in the input data.
ResNet50: A deep residual network that enables training of very deep networks by addressing the vanishing gradient problem.
EfficientNetB4: A highly efficient convolutional neural network architecture that balances model complexity and performance through compound scaling.
Data Augmentation
Data augmentation techniques have been employed to increase the diversity of the training dataset and improve the model's generalization capabilities. Augmentation techniques include rotation, flipping, scaling, and shearing of the MRI images.

Performance
VGG16 Accuracy: 94%
ResNet50 Accuracy: 89%
InceptionV3 Accuracy: 74%
EfficientNetB4 Accuracy

Usage
Installation: Clone the repository and install the required dependencies listed in the requirements.txt file.

Dataset
The dataset used for training and evaluation consists of MRI images of patients with and without brain tumors. The dataset is not provided in this repository due to privacy and licensing constraints.

Future Work
Fine-tuning hyperparameters and model architectures to further improve accuracy.
Exploring other data augmentation techniques to enhance model robustness.
