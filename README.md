# Facial Emotion Detection

An exploration of various Deep Learning architectures to classify human facial expressions using the FER (Facial Emotion Recognition) dataset.

---

## 📌 Project Overview
The goal of this project is to build and compare multiple Convolutional Neural Network (CNN) architectures to identify emotions from grayscale facial images. This project was created for learning purposes.

### 📊 Dataset
The models are trained using the **Emotion Detection FER** dataset from Kaggle.
* **Source:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer)
* **Categories:** Anger, Disgust, Fear, Happiness, Sadness, Surprise, and Neutral.

---

## 🏗️ Models Implemented
I have implemented three distinct approaches to compare performance:

1.  **ResNet50:** A 50-layer Residual Network that uses skip connections to allow for deep feature extraction without the vanishing gradient problem.
2.  **VGG16:** A classic architecture focused on 3x3 convolutional filters, known for its excellent performance in image localization and classification.
3.  **Custom CNN:** (Baseline model for performance comparison).

---

## 🚀 Getting Started

### Prerequisites
To run these notebooks, you will need:
* Python 3.8+
* TensorFlow / Keras
* OpenCV

P.S. Please note that the weight files and trained models are not included in this repository due to size constraints; you will need to run the notebooks to train the models on your own machine or in Google Colab using the provided Kaggle dataset link.
