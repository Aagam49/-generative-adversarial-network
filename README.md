# generative-adversarial-network

## Project Description
This project demonstrates the use of Generative Adversarial Networks (GANs) to synthesize realistic tree images. The GAN model was trained on the CIFAR-10 dataset, specifically focusing on the 'tree' class, to generate new, visually plausible tree images.

The project runs for 2500 epochs, ensuring stability between the generator and discriminator networks and producing high-quality outputs. This project showcases deep learning capabilities in image generation and can be extended to other object categories or higher-resolution datasets.


## Problem Statement
Generating natural images such as trees from scratch using AI is a challenging task that requires the model to learn complex textures and structures. This project aims to:

Extract tree images from CIFAR-10.
Train a GAN model to generate tree images.
Evaluate the model's ability to create realistic synthetic images.


## Technologies & Tools Used
Python
TensorFlow
NumPy
Matplotlib
CIFAR-10 Dataset (Keras/TensorFlow)
Google Colab / Jupyter Notebook
Git & GitHub

## How it Works
Load CIFAR-10 dataset and filter only the 'tree' class.
Define a Generator and Discriminator model using convolutional layers.
Train the GAN:
        Discriminator tries to differentiate between real and fake tree images.
        Generator tries to fool the discriminator.
After every few epochs, save generated images and model weights.
Evaluate final image quality visually.

## Training Summary
Dataset Used: CIFAR-10 (tree class only)
Training Epochs: 2500
Batch Size: 128
Optimizer: Adam
Loss Function: Binary Cross-Entropy (BCE)

## Author
Aagam Shah
LinkedIn: https://www.linkedin.com/in/aagam-shah-ai/
Email: saagam494@gmail.com


