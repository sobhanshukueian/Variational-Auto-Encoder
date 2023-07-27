# Variational Autoencoder (VAE) for MNIST Dataset

![MNIST Dataset](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

<div align="center">
  <strong>Implementation of a Variational Autoencoder (VAE) using PyTorch on the MNIST dataset</strong>
</div>

## Introduction

Welcome to the Variational Autoencoder (VAE) project! This repository contains an implementation of a Variational Autoencoder using PyTorch on the MNIST dataset. The Variational Autoencoder is a type of neural network architecture that combines the concept of autoencoders with variational inference. It is a generative model that learns to encode data into a lower-dimensional latent space and then decode it back to reconstruct the original data. The model's latent space is sampled from a probabilistic distribution, allowing it to generate new data samples similar to the training data.

## Purpose

The purpose of this project is to showcase the power and versatility of Variational Autoencoders in generating new data and learning meaningful representations. By training the VAE on the MNIST dataset, which consists of handwritten digits, we aim to demonstrate how the model can learn to encode different variations of the same digit and generate new, plausible digit samples.

## Key Features

- VAE architecture with encoder and decoder components.
- Utilization of the reparameterization trick for training the VAE.
- Training and evaluation on the popular MNIST dataset.
- Visualization of the latent space to understand the distribution of encoded data.
- Generation of new digit samples from random points in the latent space.

## Some Configurations
 
*   You can set epoch size: `EPOCHS` and batch size: `BATCH_SIZE`.
*   Set the `device` that you want to train the model on it: `device`(default runs on Cuda if it's available)
*   You can set one of three `verbose` that prints info you want => 0 == nothing || 1 == model architecture || 2 == print optimizer || 3 == model parameters size.
*   Each time you train model weights and plot(if `save_plots` == True) will be saved in `save_dir`.
*   You can find a `configs` file in `save_dir` that contains some information about the run. 

## Results


## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code for any purpose.

---

We hope this repository inspires you to explore Variational Autoencoders and their applications in generative modeling. Feel free to reach out if you have any questions or need further assistance.

Enjoy experimenting with VAEs and happy coding!
