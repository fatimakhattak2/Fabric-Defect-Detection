# 🧵 Fabric Defect Detection using CNN

This project is an AI-based solution for detecting fabric defects from images using a Convolutional Neural Network (CNN). It automates quality inspection in textile manufacturing by classifying fabric images into "Good" or "Defective" categories.

---

## 🔍 Features

- Binary classification: Good vs Defective fabrics
- Image preprocessing and normalization
- Dataset restructuring into binary classes
- CNN model built using TensorFlow/Keras
- Real-time prediction capability
- PDF reporting and visualization support

---

## 📁 Dataset

- The dataset is structured into image folders, each representing a defect type.
- Images are resized to `64x64` and normalized.
- Custom restructuring groups all non-good fabrics as "Defective".

---

## 🧠 Model Architecture

- `Conv2D` layers for feature extraction
- `MaxPooling2D` for spatial reduction
- `Flatten` layer
- Fully connected `Dense` layers
- `Dropout` for regularization

---

## 🚀 Getting Started

### 1. Install dependencies
```bash
pip install tensorflow keras opencv-python matplotlib reportlab
