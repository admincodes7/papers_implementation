# Image Generation Using Diffusion Models

This repository contains the code for generating images using Diffusion Probabilistic Models (DDPM). The code is based on the paper [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239) by Jonathan Ho, Ajay Jain, and Pieter Abbeel and the paper [Improved Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2102.09672) by Alex Nichol, Prafulla Dhariwal


## Understanding Diffusion Models
For a comprehensive understanding of Diffusion Probabilistic Models (DDPMs), I've written an article that covers:
- The theoretical foundations of diffusion models
- Step-by-step explanation of the forward and reverse processes
- Mathematical intuition behind the noise prediction and derivation

👉Read full article here: [Understanding Diffusion Probabilistic Models](https://medium.com/@hemanthsbanur/diffusion-probabilistic-models-from-ink-drops-to-ai-c337750b317e)


## Setup and Installation
1. Clone the repository

2. Install the required packages
```bash
pip install -r requirements.txt
```
3. Configuration
Head to the `config.yaml` file to configure the model hyperparameters and training parameters.
4. Load the dataset into the `data` folder. The dataset should be in the form of a folder containing the images.
5. Training
```bash
python train.py
```
