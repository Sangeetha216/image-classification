<div align="center">

# 🖼️ Image Classification into 6 Categories
### 🧠 Deep Learning &nbsp;•&nbsp; 🔷 CNN &nbsp;•&nbsp; 🔄 Transfer Learning &nbsp;•&nbsp; 👁️ Computer Vision

<p>
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white">
  <img src="https://img.shields.io/badge/Computer%20Vision-4CAF50?style=for-the-badge">
  <img src="https://img.shields.io/badge/Transfer%20Learning-ResNet50%20%7C%20MobileNetV2-9C27B0?style=for-the-badge">
</p>

</div>

---

## 📌 Project Overview

This project tackles **multiclass image classification** using Deep Learning to sort images into six categories. It walks through the full modeling journey — from a simple **ANN baseline** to **custom CNN architectures** and finally **transfer learning** with pretrained networks — comparing performance and design trade-offs at each stage.

---

## 🗂️ Dataset

The dataset consists of images across six categories:

| Category | Description |
|---|---|
| 🏢 Building | Urban structures and architecture |
| 🌲 Forest | Dense tree cover and woodland |
| ❄️ Glacier | Ice formations and glacial landscapes |
| 🏔️ Mountain | Mountain ranges and terrain |
| 🌊 Sea | Coastal and open water scenes |
| 🏙️ Street | Urban street-level imagery |

Images were preprocessed (resizing, normalization) and split into training and test sets prior to model development.

---

## 🧠 Models Explored

- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)
- Improved CNN
- CNN with Data Augmentation
- MobileNetV2
- ResNet50

---

## 🔄 Project Workflow

```text
Image Dataset
      ↓
Data Understanding
      ↓
Image Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Train / Test Split
      ↓
ANN Baseline
      ↓
CNN
      ↓
Improved CNN
      ↓
Data Augmentation
      ↓
Transfer Learning
      ↓
MobileNetV2
      ↓
ResNet50
      ↓
Model Evaluation
      ↓
Single Image Prediction
