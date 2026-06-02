# AI-Generated vs Authentic Face Detection using Deep Learning

A Computer Vision and Deep Learning project that leverages Convolutional Neural Networks (CNNs) to distinguish AI-generated facial images from authentic human photographs.

## Overview

The rapid advancement of Generative AI models has enabled the creation of highly realistic synthetic facial images. While these technologies unlock new possibilities, they also introduce challenges related to content authenticity, misinformation, and digital trust.

This project explores the use of Deep Learning techniques to classify facial images as either:

* Authentic Human Faces
* AI-Generated / Synthetic Faces

The system utilizes a Convolutional Neural Network (CNN) built using TensorFlow and Keras to learn discriminative visual patterns from facial imagery and perform binary image classification.

## Key Features

* AI-Generated vs Authentic Face Classification
* Convolutional Neural Network (CNN) Architecture
* Image Preprocessing and Data Augmentation
* TensorFlow & Keras Implementation
* Model Checkpointing
* Validation and Performance Monitoring
* Prediction on Unseen Images
* Google Colab Compatible Workflow

## Technology Stack

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab
* Deep Learning
* Computer Vision

## Problem Statement

Generative AI systems can now create highly realistic facial images that are often difficult to distinguish from genuine photographs.

The objective of this project is to develop a Deep Learning-based image classification model capable of identifying whether a facial image is:

* Authentic (Human-Captured)
* AI-Generated (Synthetic)

## Deep Learning Pipeline

```text
Input Face Image
        │
        ▼
Image Preprocessing
        │
        ▼
Data Augmentation
        │
        ▼
CNN Feature Extraction
        │
        ▼
Dense Classification Layers
        │
        ▼
Authentic / AI-Generated Prediction
```

## Dataset

The model was trained on an open-source facial image dataset obtained from publicly available Kaggle resources.

The dataset consists of two image categories:

* Authentic Human Faces
* AI-Generated / Synthetic Faces

The dataset is not included in this repository due to size limitations and licensing considerations.

## Model Architecture

The implemented CNN architecture includes:

* Convolutional Layers
* ReLU Activation Functions
* Max Pooling Layers
* Flatten Layer
* Fully Connected Dense Layers
* Binary Classification Output Layer

The model was developed using TensorFlow and Keras for binary image classification tasks.

## Training Strategy

The training workflow incorporates:

* Image Rescaling
* Data Augmentation
* Batch Processing
* Validation Monitoring
* Model Checkpointing
* Accuracy and Loss Tracking

These techniques help improve model robustness and reduce overfitting.

## Applications

* AI-Generated Content Detection
* Synthetic Media Identification
* Deep Learning Research
* Computer Vision Applications
* Digital Media Verification
* AI Safety Research
* Misinformation Detection
* Content Authenticity Analysis

## Repository Structure

```text
ai-generated-face-detection/
│
├── ai_generated_face_detection.ipynb
├── requirements.txt
└── README.md
```

## Installation

```bash
pip install -r requirements.txt
```

## Usage

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Configure dataset paths according to your environment.
3. Execute the notebook cells sequentially.
4. Train the CNN model.
5. Evaluate performance on validation data.
6. Perform predictions on custom facial images.

## Future Improvements

* Transfer Learning using EfficientNet
* Vision Transformers (ViTs)
* Explainable AI (XAI)
* Real-Time Detection Pipeline
* FastAPI Deployment
* Model Optimization and Quantization

## Skills Demonstrated

* Deep Learning
* Computer Vision
* CNNs
* Image Classification
* TensorFlow
* Keras
* Data Augmentation
* Model Training
* Model Evaluation
* AI Safety Concepts

## Author

Anoushka Kaul

B.Tech Computer Science (AI/ML & Data Science)

Interests: Generative AI, Agentic AI, Computer Vision, Deep Learning, and Multi-Agent Systems.
