# Text-to-Image Generation Using Stable Diffusion

## Project Overview

This project implements a text-to-image generation system using Stable Diffusion and Realistic Vision V5.1. The system generates images from natural-language prompts and demonstrates the effect of prompt engineering and generation parameters on image quality.

## Technologies Used

- Python
- Stable Diffusion
- Realistic Vision V5.1
- Hugging Face Diffusers
- PyTorch
- Gradio
- Kaggle GPU (Tesla T4)

## Features

- Text-to-image generation
- Prompt engineering
- Photorealistic image generation
- Negative prompt handling
- Adjustable inference steps
- Adjustable guidance scale
- Interactive Gradio interface
- Evaluation of inference steps and guidance scale

## Evaluation

The project evaluates image generation using different:

- Inference steps: 20, 35, and 50
- Guidance scales: 5.0, 7.5, and 10.0

The generated results are compared to understand how these parameters affect image quality and generation time.

## Model

**Realistic Vision V5.1**

`SG161222/Realistic_Vision_V5.1_noVAE`

## Project Notebook

The complete implementation is available in:

`text-to-image-ipynb.ipynb`

## Deployment

The application was tested using a Gradio interface running on a Kaggle GPU environment.
