# 🫁 Lung-Cancer-Detection with Grad-CAM Interpretability

## 🩺 Overview
This project focuses on building a deep learning model to detect lung cancer from histopathological images. To make the model’s decisions more transparent and interpretable, GradCAM (Gradient-weighted Class Activation Mapping) is used, allowing us to visualize which regions of the images influenced the model’s predictions the most.

## ✨ Features
- Accurate lung cancer classification using convolutional neural networks (CNNs) on histopathological lung images
- Interpretability via GradCAM, highlighting important areas in the images that lead to classification
- Preprocessing pipeline tailored for lung cancer image data 
- Clear visualization of GradCAM heatmaps overlayed on original images

## 🏥 Dataset
- Lung and Colon Cancer Histopathological Images (from Kaggle) - [Link](https://www.kaggle.com/code/sinchubhat/lung-colon-cancer-histopathological-images-monk)
- Focus on lung images from the following subsets:
  - Lung Adenocarcinoma (lung_aca)
  - Lung Squamous Cell Carcinoma (lung_scc)
  - Benign Lung Tissue (lung_n)
- Images are preprocessed and split into training, validation, and testing sets

## 🎯 Model Architecture
- CNN-based architecture (e.g., ResNet, VGG, or customCNN)
- Trained to distinguish lung cancer from normal tissue
- Uses transfer learning or training from scratch, depending on data and experiment setup

## 📝 GradCAM Interpretability
- Generates heatmaps showing which regions of the image most influenced the model’s decision
- Helps clinicians and researchers understand and trust the model’s predictions
- Implemented using gradient-based backpropagation through the last convolutional layers

## 📈 Results
- Achieved high accuracy and recall on lung cancer classification (Train Accuracy: 99.99%, Test Accuracy: 96.84%)
- GradCAM visualizations confirm model focuses on cancerous tissue regions
- Results provide meaningful insights into model decision-making

## 🙌 Credits
Project by Sri – an aspiring Data Scientist exploring AI in creative ways!
