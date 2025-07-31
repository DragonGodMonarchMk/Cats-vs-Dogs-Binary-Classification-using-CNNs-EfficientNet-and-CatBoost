# Cats-vs-Dogs-Binary-Classification-using-CNNs-EfficientNet-and-CatBoost
A hybrid deep learning + machine learning approach for classifying cat and dog images using CNNs, EfficientNet, and CatBoost. This project compares multiple models to evaluate performance and generalization.
# 🐱🐶 Cats vs Dogs: Binary Image Classification

This repository explores a hybrid approach to solving the classic Cats vs Dogs binary classification problem using Convolutional Neural Networks (CNNs), EfficientNet (a state-of-the-art deep CNN), and CatBoost (a gradient boosting framework). The aim is to compare traditional CNN models with more advanced architectures and ensemble techniques for improved performance.

---

## 📌 Key Features

- 📁 Image preprocessing using TensorFlow and Keras
- 🧠 CNN-based binary classification model
- ⚡ EfficientNetB0-based transfer learning model
- 🐤 CatBoost classifier using extracted image features
- 📈 Evaluation metrics and visualizations (accuracy, confusion matrix, etc.)
- ✅ End-to-end workflow from data loading to model saving

---

## 📁 Project Files

- `binaryclassification-cats-vs-dogs-data.ipynb`: Implements a basic CNN for cat-vs-dog classification.
- `cat-dog-efficientnet-catboost.ipynb`: Builds a hybrid pipeline combining EfficientNet and CatBoost for performance enhancement.

---

## 🔧 Installation & Requirements

Install the required Python libraries:

```bash
pip install tensorflow keras catboost scikit-learn matplotlib opencv-python
