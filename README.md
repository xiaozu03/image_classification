# image_classification
Simple VLM Project for practice

# Image Classification with Hugging Face

## Overview
In this practice project, you'll explore the capabilities of Visual Transformers (ViT) for various image understanding tasks. It aims to demonstrate the versatility of ViT models by showcasing their performance in simple image classification, zero-shot image classification, and zero-shot object detection tasks. By the end of the project, you'll understand the potential of ViT models in handling diverse image-related challenges.

## Tasks Covered
- **Simple Image Classification:** This task involves using a ViT model to classify images into predefined categories. It serves as a foundational example of using ViT for image understanding.
- **Zero-Shot Image Classification:** Here, the project explores the ViT model's ability to classify images into categories it has never seen during training. This task demonstrates the model's capability to generalize to new classes, a crucial skill in real-world scenarios.
- **Zero-Shot Object Detection:** This task goes beyond classification and involves localizing and identifying objects within images, even if the model has never encountered those objects during training. It showcases the ViT model's potential for object detection in novel contexts.

## Target Audience
This project targets individuals with an intermediate to advanced level of knowledge in machine learning and computer vision. This includes data scientists, machine learning engineers, computer vision researchers, or anyone interested in exploring the capabilities of state-of-the-art ViT models for image-related tasks. 

**Prerequisites:**
- Basic understanding of deep learning concepts
- Coding proficiency in Python

## Setup and Dependencies
To run this project, you will need the following Python packages installed:
- `transformers` (Hugging Face)
- `Pillow` (PIL)
- `requests`
- `torch` (PyTorch)
- `matplotlib`

## Getting Started
1. Install the required dependencies.
2. Open `notebook.ipynb` in Jupyter Notebook or your preferred environment.
3. Run the cells sequentially to load the pre-trained Vision Transformer (`google/vit-base-patch16-224`), generate features from images, and perform classifications!
