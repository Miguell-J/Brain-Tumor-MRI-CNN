# 🧠 Brain Tumor Detection using Deep Learning

![image](https://github.com/user-attachments/assets/42bdf5d4-fdfe-42f4-87de-c3f34d25b3ca)


## Overview

This project implements a sophisticated Convolutional Neural Network (CNN) for automated brain tumor detection from MRI images, leveraging advanced deep learning techniques to distinguish between healthy and tumor-affected brain scans.

## 🚀 Project Highlights

- **Advanced Neural Network Architecture**: Custom-designed CNN with multiple convolutional and fully connected layers
- **High-Performance Image Classification**: Precise detection of brain tumors from MRI scans
- **Robust Training Methodology**: Comprehensive training and validation process
- **State-of-the-Art Deep Learning Techniques**: Utilizing PyTorch and modern computer vision approaches

## 📊 Technical Specifications

### Model Architecture
- **Input Layer**: RGB image preprocessing (224x224 pixels)
- **Convolutional Layers**: 
  - 1st Layer: 3 input channels → 32 filters
  - 2nd Layer: 32 filters → 64 filters
  - 3rd Layer: 64 filters → 128 filters
- **Pooling**: MaxPooling for feature extraction
- **Fully Connected Layers**: 
  - First layer: Dimensionality reduction
  - Output layer: Binary classification (Tumor/No Tumor)

### Training Parameters
- **Loss Function**: Cross-Entropy Loss
- **Optimizer**: Adam (Learning Rate: 0.0001)
- **Epochs**: 10
- **Batch Size**: 32
- **Train/Validation Split**: 80/20

## 🔍 Key Features

- Automatic image resizing and normalization
- Dynamic device selection (CUDA/CPU)
- Best model weight preservation
- Comprehensive performance tracking

## 📈 Performance Metrics

The model tracks:
- Training Loss
- Training Accuracy
- Validation Loss
- Validation Accuracy

## 🛠 Dependencies

- Python 3.x
- PyTorch
- torchvision
- zipfile
- os

## 🚀 Quick Start

1. Prepare your MRI image dataset
2. Ensure required dependencies are installed
3. Configure dataset path
4. Run the script
5. Monitor training progress and final validation accuracy

## 💡 Potential Improvements

- Implement data augmentation
- Experiment with transfer learning
- Explore more complex architectures
- Add more detailed performance metrics


## 🤝 Contributing

Contributions, issues, and feature requests are welcome!


---

**Disclaimer**: This is a research project and should not be used for medical diagnosis without professional medical consultation.
