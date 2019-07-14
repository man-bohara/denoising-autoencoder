# Udacity DLND Denoising Autoencoder Project

## Overview
This is a deep learning model to de-noise images.

## Instructions
1. Install Anaconda and create conda environment.

2. Install numpy, matplotlib, pytorch.

3. Clone the repository
```
git clone https://github.com/man-bohara/denoising-autoencoder.git
```

4. Run following command
```
jupyter notebook Denoising_Autoencoder.ipynb
```

5. Follow instructions on the notebook.

## Model Architecture
This model is comprised of two components.
1) Encoder - Encoder consists of 3 convolution layers with max pooling.
2) Decoder - Decoder consists of 3 transpose convolution layers.

ReLU Activation functions is applied to all the conv and transpose conv layers except the last convolution layer.
In the last convolution layer, Sigmoid activation is applied.

## Training
I trained the model on MNIST image dataset.
