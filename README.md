# Autoencoders

This repository contains a collection of autoencoder models implemented in TensorFlow. The first model is trained on the MNIST dataset. 

## Simple MNIST Autoencoder

The first model is a simple autoencoder that takes in a 28x28 image and outputs a 28x28 image. The model is trained on the MNIST dataset. The model is implemented in `simple_autoencoder.ipynb`.

## Autoencoder Rundown

Here I go over the current literature regarding the basics of autoencoders , image denoising, and anamoly detection. The model is implemented in `autoencoder_rundown.ipynb`. The first model `Basic Autoencoder` utilizes the `Keras Model Subclassing API` to define both the encoder and decoder models within an autoencoder class.

## Experiments

Now that the rundown is complete. Let's explore possible datasets to use for training more autoencoders. For every possible dataset that I find, I will create a data preperation workflow for each. Once one of the datasets is chosen for training, I will then create a fleshed out model and present it for a possible portfolio project.

### Autoencoder Image Segmentation