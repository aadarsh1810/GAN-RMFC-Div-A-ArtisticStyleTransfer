# CycleGAN for Artistic Style Transfer with Monet Paintings Dataset

This repository contains an implementation of CycleGAN for artistic style transfer using the Monet paintings dataset. CycleGAN is a type of generative adversarial network (GAN) that learns to translate images from one domain to another without paired data.

## Overview

CycleGAN consists of two generator networks (G_AB and G_BA) and two discriminator networks (D_A and D_B). The generators learn to translate images from domain A (e.g., photographs) to domain B (e.g., Monet paintings) and vice versa. The discriminators aim to distinguish between the translated images and real images from their respective domains.

## Requirements

- Python 3.x
- PyTorch
- torchvision
- numpy
- matplotlib
