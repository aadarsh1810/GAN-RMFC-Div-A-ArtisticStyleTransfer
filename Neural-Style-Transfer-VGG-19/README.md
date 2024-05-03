# VGG-19 Neural Style Transfer

This repository contains an implementation of neural style transfer using the VGG-19 convolutional neural network architecture. Neural style transfer is a technique that combines the content of one image with the style of another image. In this implementation, we use a pre-trained VGG-19 model to extract feature representations from both the content and style images.

## Overview

Neural style transfer works by defining a loss function that balances the content loss (measuring the similarity between the content of the content image and the generated image) and the style loss (measuring the similarity between the style of the style image and the generated image). By minimizing this combined loss function, we can generate an image that preserves the content of the content image while adopting the style of the style image.

## Requirements

- Python 3.x
- PyTorch
- torchvision
- numpy
- PIL (Python Imaging Library)
