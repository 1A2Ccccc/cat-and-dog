# Cat vs Dog Image Classification Project

## 1. Project Overview
This project implements a Deep Learning model to classify images of cats and dogs using the CIFAR-10 dataset.
It achieves **High Accuracy (approx. 90%)** by comparing a custom TinyVGG model with Transfer Learning (ResNet50V2/MobileNetV2).

## 2. Key Features
- **Data Augmentation**: Random flip, rotation, and zoom to improve generalization.
- **Model Comparison**: 
  - Baseline: Custom TinyVGG (CNN)
  - SOTA: Transfer Learning with ResNet50V2
- **Interpretability**: Implemented **Grad-CAM** to visualize model attention (Heatmaps).

## 3. Results
- **TinyVGG Accuracy**: ~83%
- **Transfer Learning Accuracy**: ~80%

## 4. Environment
- TensorFlow / Keras
- Matplotlib / Seaborn
- NumPy

## 5. Author
Li Tianqi,Zhang Junkai,Tian Zhaojun
