# Variational Autoencoder (VAE) for MNIST Handwritten Digit Generation

## Overview

This project implements a Variational Autoencoder (VAE) to generate new handwritten digits using the MNIST dataset. The VAE is a generative model that learns a lower-dimensional representation of high-dimensional data, allowing for the generation of new samples by interpolating within the learned latent space.

## Features

- **Image Compression and Reconstruction**: Compresses 28x28 pixel grayscale images of handwritten digits into a latent space and reconstructs them accurately.
- **Latent Space Exploration**: Generates new images by varying latent variables and interpolating between existing data points.
- **Visual and Quantitative Evaluation**: Assesses generated images qualitatively through visual inspection and quantitatively using reconstruction loss and KL divergence metrics.

## Technologies Used

- **Programming Language**: Python
- **Frameworks and Libraries**:
  - TensorFlow
  - Keras
  - NumPy
  - Matplotlib

## Files Included

- `vae.py`: Main Python script containing the implementation of the VAE.
- `requirements.txt`: File listing the required Python packages for the project.

## Installation

To set up the project environment, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the main script:
   ```bash
   python vae.py
   ```

2. The model will train on the MNIST dataset for 10 epochs, displaying the generated images at the end.

## Example Output

The output will showcase a grid of newly generated handwritten digits created by varying the latent variables in the VAE's latent space.

## License

This project is licensed under the MIT License. Feel free to modify and distribute as per the license terms.

## Acknowledgments

- The MNIST dataset can be accessed through the [Yann LeCun's website](http://yann.lecun.com/exdb/mnist/).
- Special thanks to the TensorFlow and Keras communities for their comprehensive documentation and support.
