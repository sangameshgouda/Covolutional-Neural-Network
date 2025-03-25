### Convolutional-Neural-Network

### Project Overview

This repository contains multiple Convolutional Neural Networks (CNNs) implementations for image classification tasks using popular datasets such as CIFAR-10 and Caltech101. The models are built and evaluated using PyTorch, covering basic CNNs, data augmentation techniques, and pretrained models.

### File Structure & Highlights

1. cnn_cifar10_classification-simple_model.ipynb

Implements a simple CNN from scratch to classify images from the CIFAR-10 dataset.

Training and evaluation pipeline included.

2. Data-Augmentation.ipynb
   
Builds on the previous model by:

Comparing training with vs without data augmentation.

Applies techniques like random crop, horizontal flip, and normalization.

3. Transfer-Learning.ipynb
   
Image classification on the Caltech101 dataset using:

A custom CNN.

Pretrained models: ResNet18 and EfficientNet for transfer learning.

Highlights performance boost using pretrained networks.

### Features

Custom CNN architectures for small and mid-scale datasets.

Data augmentation for improved generalization.

Transfer learning using ResNet18 and EfficientNet.

Clean, modular code with training and validation loops.

Easily adaptable for other image classification tasks.
