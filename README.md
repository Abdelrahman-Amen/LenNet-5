# LenNet-5  ♠
# LeNet Image Classification

## Overview

This repository contains an implementation of the LeNet convolutional neural network architecture for image classification. LeNet, developed by Yann LeCun and his colleagues, was one of the pioneering models in the field of convolutional neural networks (CNNs) and played a crucial role in the advancement of computer vision tasks.

The primary focus of this project is to demonstrate the effectiveness of the LeNet architecture in classifying images, particularly those containing characters and digits. The model is trained and evaluated on a dataset with grayscale images to showcase its capabilities in recognizing and classifying numerical patterns.


## Dataset

The project utilizes a dataset containing grayscale images, focusing on characters and digits. This dataset serves as the foundation for training and evaluating the LeNet model's performance in image classification tasks. 

## LeNet Architecture

LeNet is a convolutional neural network architecture that consists of several layers, including convolutional layers, pooling layers, and fully connected layers. The model is known for its ability to effectively capture hierarchical features in images, making it particularly suitable for tasks such as digit recognition.

![download (2)](https://github.com/Abdelrahman-Amen/LenNet-5/assets/103226865/611872e6-926f-4ee8-aa4b-c48c9e8c8c88)
![download (1)](https://github.com/Abdelrahman-Amen/LenNet-5/assets/103226865/5e6bd443-3ddc-4ced-a7aa-95b03f58ef42)



### Model Summary

When using the LeNet-5 model on the MNIST dataset, we achieved an accuracy above 90%. This is a relatively high accuracy, which indicates that the LeNet-5 model is performing well on the MNIST dataset. The MNIST dataset consists of grayscale images of handwritten digits (0-9), and it is a relatively simple and well-studied dataset. The LeNet-5 architecture, with its convolutional and pooling layers, is specifically designed for image recognition tasks, making it effective for the MNIST dataset.


The variation in accuracy between datasets can be attributed to their inherent characteristics. MNIST, a simpler dataset featuring grayscale images primarily containing digits, allows for an easier learning process with less variability, making it conducive for accurate digit classification using architectures like LeNet. However, it's important to note that architectures optimized for datasets like MNIST, which focus on characters and digits, may not generalize well to datasets without such numerical patterns or structures. Achieving higher accuracy on datasets with different characteristics often requires the implementation of more advanced models or techniques capable of capturing intricate patterns and features specific to the nature of the new dataset.







