---
layout: page
title: Custom CNN model
permalink: /projects/cnn-classification/
---

This project was completed as part of a Kaggle competition organized by the university. The goal was to build a deep learning model to classify images into 20 categories.

## 📌 Highlights
- Used a custom CNN architecture in PyTorch
- Applied data augmentation, dropout, and early stopping
- Achieved over **75.8% accuracy** on the private test set

## 🧠 Model Details

- **Architecture**: Conv2D layers + BatchNorm2D + ReLU + MaxPooling → Fully connected layers
- **Optimizer**: AdamW
- **Loss**: CrossEntropyLoss
- **LR Scheduler**: CosineAnnealingLR
- **Epochs**: [100]
- **Input shape**: [3x40x40]

## 📁 Notebook
Click to download the full training and evaluation notebook:

👉 [kaggle-challenge1-final.ipynb](./kaggle-challenge1-final.ipynb)

---

**Author**: Haridhanush Ravichandran  
Master's in Data Science, University of Padova (2024–26)  
📌 Interests: ML, DL, NLP,KRL
