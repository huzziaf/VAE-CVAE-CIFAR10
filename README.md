# CIFAR-10 Image Generation with Variational Autoencoders (VAE) and Conditional Variational Autoencoders (CVAE)

This repository contains the implementation of Variational Autoencoders (VAEs) and Conditional Variational Autoencoders (CVAEs) for the CIFAR-10 dataset. The project covers data preprocessing, model training, evaluation, and analysis of generated images.

## Dataset

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 50,000 training images and 10,000 test images. For both VAE and CVAE implementations, the dataset is divided into 80% training and 20% testing subsets.

## VAE Implementation Steps

### 1. Data Preprocessing

- Normalize the CIFAR-10 dataset.

### 2. VAE Model Training

- Train the VAE model using both reconstruction loss and KL divergence.

### 3. Loss Visualization

- Plot reconstruction loss and KL divergence for each epoch.

### 4. Image Generation

- Visualize 5 randomly selected generated images and 5 real images.

### 5. Quality Evaluation

- Measure the quality of generated images using Fréchet Inception Distance (FID).

## CVAE Implementation Steps

### 1. Data Preprocessing

- Prepare images and labels for training with the CVAE.

### 2. CVAE Model Training

- Implement a CVAE that uses class labels as conditions.

### 3. Hyperparameter Tuning

- Tune hyperparameters such as learning rate and latent space dimensionality.

### 4. Image Generation and Analysis

- Generate and display images from each class.
- Analyze the quality, diversity, and class accuracy of the generated images.
