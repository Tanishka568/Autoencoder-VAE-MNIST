# Autoencoder and Variational Autoencoder for MNIST

## About the Project

This project implements a Fully Connected Autoencoder (AE) and a
Variational Autoencoder (VAE) using PyTorch and the MNIST dataset.

The models are trained to reconstruct handwritten digit images.
The VAE is also used to generate new handwritten digit samples.

## Objectives

- Understand Autoencoders and Variational Autoencoders.
- Implement an Autoencoder using PyTorch.
- Implement a Variational Autoencoder using PyTorch.
- Train both models on the MNIST dataset.
- Visualize original and reconstructed images.
- Generate new handwritten digit images using the VAE.
- Observe the training loss trends.

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Google Colab

## Dataset

The MNIST dataset contains grayscale images of handwritten digits
from 0 to 9.

- Training images: 60,000
- Testing images: 10,000
- Image size: 28 × 28 pixels
- Number of classes: 10

The dataset is downloaded automatically using Torchvision.

## Models Implemented

### 1. Autoencoder (AE)

The Autoencoder consists of an encoder and a decoder.
The encoder compresses an input image into a smaller representation,
and the decoder reconstructs the original image.

The model uses Mean Squared Error (MSE) loss.

### 2. Variational Autoencoder (VAE)

The VAE learns a probability distribution in its latent space.
It uses an encoder, latent sampling, and a decoder.

The VAE can reconstruct input images and generate new samples
from randomly sampled latent vectors.

Its loss combines reconstruction loss and KL divergence.

## Implementation Steps

1. Load the MNIST dataset.
2. Display sample images.
3. Build and train the Autoencoder.
4. Display reconstructed images.
5. Build and train the VAE.
6. Display VAE reconstructions.
7. Generate new images using the VAE.
8. Compare training loss trends.

## Results

Both models were implemented and trained on the MNIST dataset.
The Autoencoder was used for image reconstruction, while the VAE
was used for reconstruction and image generation.

The loss values use different calculations, so their magnitudes
should not be directly compared.

## How to Run

1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Allow the MNIST dataset to download.
4. View the reconstructed images, generated samples, and loss graph.

## Requirements

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib

## Conclusion

The practical demonstrates image reconstruction using an Autoencoder
and image reconstruction and generation using a Variational Autoencoder.
