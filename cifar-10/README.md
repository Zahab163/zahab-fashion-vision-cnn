# CIFAR-10 CNN

This folder contains experiments using Convolutional Neural Networks (CNNs) to classify images from the CIFAR-10 dataset.

## Dataset
- 60,000 color images (32x32 pixels)
- 10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck
---
## Model

- Convolutional + MaxPooling layers for feature extraction
- Dense + Softmax for classification
- Optimizer: Adam
- Loss: Categorical Crossentropy
  
---

## Results

- Accuracy ~70–80% with a simple CNN
- Improvements possible with Data Augmentation, Batch Normalization, and deeper architectures
--- 

### Next Steps

- Add Grad-CAM visualizations
- Compare with transfer learning models (ResNet, MobileNet)
