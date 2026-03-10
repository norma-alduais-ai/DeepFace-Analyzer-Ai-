DeepFace Analyzer AI

A deep learning project for facial emotion recognition using a ResNet18-based model.

Project Overview

This project builds an AI system capable of detecting human emotions from facial images.

Supported emotions:

- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral

Model

The model is based on ResNet18 and was fine-tuned using PyTorch.

Main steps:

1. Image preprocessing
2. Emotion classification
3. Prediction output

Dataset

The model was trained using the FER2013 dataset which contains thousands of labeled facial emotion images.

Training

Training settings:

- Image size: 64x64
- Batch size: 64
- Optimizer: Adam
- Loss: CrossEntropyLoss

Results

Test Accuracy: ~57%

Technologies

- Python
- PyTorch
- Torchvision
- OpenCV
- Google Colab

Future Improvements

- Real-time emotion detection
- Larger datasets
- Deploy as a web app
