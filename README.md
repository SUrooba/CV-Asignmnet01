# CV-Asignmnet01
# 🚦 Traffic Sign Image Classifier – Computer Vision Project

This project implements a Convolutional Neural Network (CNN) to classify German traffic signs into 43 categories using the GTSRB dataset. It was developed as part of a computer vision assignment during my MSc in Artificial Intelligence.

---

## 📁 Dataset

- **Source**: [German Traffic Sign Recognition Benchmark (GTSRB)](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)
- 43 classes
- ~50,000 labeled images
- All images resized to 32x32 pixels

---

## 🧠 Model Overview

- Deep learning model using CNN
- Layers: 
  - Conv2D + ReLU
  - MaxPooling
  - Dropout
  - Flatten → Dense
- Loss: `CategoricalCrossentropy`
- Optimizer: `Adam`

---

## 🧪 Performance

| Metric        | Value        |
|---------------|--------------|
| Train Accuracy| 98%+         |
| Val Accuracy  | ~93–95% (varies by
