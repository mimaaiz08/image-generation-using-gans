# Image Generation Using GANs

A deep learning mini project exploring image generation using
Deep Convolutional Generative Adversarial Networks (DCGAN) and
Wasserstein GAN with Gradient Penalty (WGAN-GP).

## Project Overview

The project experiments with generating cake images from a small
dataset of approximately 231 images, resized to 64x64 RGB.

## Models and Experiments

- DCGAN training experiments
- WGAN-GP training experiments
- Generator output comparisons
- Training loss visualizations
- Generated sample images

## Current Results

The current experiments have not yet produced recognizable cake
images. The generated outputs show that the models require further
training and tuning. The plots and samples are included to document
the experimental process, not to claim successful image generation.

## Project Structure

- `plots/` — training and model comparison plots
- `generated_samples/` — saved sample outputs from experiments
- `checkpoints/` — selected generator checkpoint
- `experiment_summary.json` — experiment summary

## Requirements

- Python 3
- PyTorch
- torchvision
- NumPy
- Matplotlib
- Pillow

## Running the Project

The experiments were developed in Google Colab with GPU support.
The original notebook containing the complete training workflow
should be included in this repository when available.

## Dataset

The project uses cake images for experimentation. Check the original
dataset source and its license before redistributing the images.

## Author

Maaiz — AIML Engineering Student
