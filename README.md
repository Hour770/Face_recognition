# Face Encoding and Recognition using CNN

This repository contains a comprehensive implementation of face encoding and recognition using Convolutional Neural Networks (CNNs). The project utilizes a Siamese network architecture to effectively convert face images into unique feature vectors, facilitating accurate face recognition tasks.

## Overview
Facial recognition technology is crucial for security, authentication, and user verification applications. This project implements a CNN-based approach for face encoding, achieving robust performance under various lighting, orientation, and expression conditions.

## Features
- CNN-based Siamese network for face encoding
- Data augmentation for improved generalization
- Robust evaluation metrics (Accuracy)
- Efficient feature extraction and encoding process

## Dataset
The dataset used is self-collected:
- Approximately 50 images per individual (augmented to 500 per class)
- Image format: JPG
- Resolution: 225x225 pixels

Data augmentation techniques include rotation, scaling, and noise addition.

## Methodology
- **Architecture:** Siamese CNN network
- **Layers:** 4 convolutional layers with ReLU activation and max-pooling, followed by two dense layers with 128 neurons each
- **Optimizer:** Adam (Learning rate: 0.001)
- **Loss Function:** Contrastive loss

## Requirements
- Python 3.x
- TensorFlow
- Keras
- NumPy
- OpenCV

Install dependencies using:
```bash
pip install -r requirements.txt
```

## How to Run
Clone the repository:
```bash
git clone https://github.com/Hour770/face_encode.git
```



## Results
| Metric | Score |
|--------|-------|
| Accuracy | 94% |



## Future Work
- Implement deeper CNN architectures
- Incorporate additional augmentation techniques
- Optimize for real-time performance

## Acknowledgments
- Special thanks to all collaborators and contributors for guidance and support.
