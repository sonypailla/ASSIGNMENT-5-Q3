# ASSIGNMENT-5-Q3
Programming Task (Basic GAN Implementation)
# Basic GAN on MNIST

## Student Info
- Name:SONY PAILLA
- Course: [CS5720 Neural Networks and Deep Learning]
- Semester: Spring 2025
- University: University of Central Missouri

## Project Description
This project implements a simple Generative Adversarial Network (GAN) using PyTorch to generate handwritten digits based on the MNIST dataset.

## Features
- Basic Generator and Discriminator
- Training loop with alternating updates
- Sample images generated at Epoch 0, 50, and 100
- Loss plots comparing Generator and Discriminator

## How to Run
1. Install the requirements
2. Run the script
3. 
## Outputs
- Generated images saved at `samples/epoch_0.png`, `epoch_50.png`, `epoch_100.png`
- Loss comparison graph saved as `loss_plot.png`

## Architecture
- Generator: 3 fully connected layers with ReLU activations, Tanh at output.
- Discriminator: 3 fully connected layers with LeakyReLU activations, Sigmoid output.

## Notes
- Training set: MNIST handwritten digits
- Latent vector size: 64
- Batch size: 100
- Number of epochs: 100


