# Deep Convolutional VAE

## Overview

This repository contains implementations of **Deep Convolutional Variational Autoencoders (VAE)**, focusing on image generation and interpolation tasks. The project includes Jupyter notebooks that train and evaluate Convolutional VAEs on datasets like CIFAR-10 and Fashion MNIST. The goal of the models is to learn latent representations of data and generate new, realistic images based on these learned representations.

## Objective

The objective of this project is to:

- Implement a Convolutional VAE (CVAE) that can learn an efficient latent representation of images.
- Train the model on popular datasets like **CIFAR-10** and **Fashion MNIST**.
- Generate new images by sampling points from the latent space.
- Interpolate between images in the latent space to visualize smooth transitions.

This work can be useful for tasks such as data generation, denoising, and exploring latent spaces of generative models.

## Directory Structure

```plaintext
│
├── 032---Assignment-3---Variational-Autoencoders.pdf  # Assignment instructions and details.
├── README.md  # This file
├── requirements.txt  # List of dependencies for the project
└── src  # Source code and Jupyter notebooks
    ├── conv_variational_autoencoder.ipynb  # Convolution and Fully Connected VAE on CIFAR-10 dataset.
    └── conv_variational_autoencoder_fMNIST.ipynb  # Convolution and Fully Connected VAE on Fashion-MNIST dataset.
```

## Requirements

Before running the code, ensure you have the necessary dependencies installed. You can install them using:

```bash
pip install -r requirements.txt
```