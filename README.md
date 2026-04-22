# cat-dog-classification-cnn
CNN-based image classification project to distinguish between cats and dogs using TensorFlow and Keras. Implements data augmentation, validation split, and binary classification with ~85–90% accuracy.


## 📌 Overview
This project implements a Convolutional Neural Network (CNN) to classify images of cats and dogs using a public dataset from Kaggle.

## 🚀 Features
- Automatic dataset download using KaggleHub
- Image preprocessing with augmentation (flip, shift)
- Binary image classification (Cat vs Dog)
- Model evaluation using validation accuracy

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- CNN (Deep Learning)
- KaggleHub

## 📂 Dataset
Cat vs Dog Images Dataset (Kaggle)

## ⚙️ Model Architecture
- Conv2D (32 filters) + MaxPooling
- Conv2D (64 filters) + MaxPooling
- Flatten + Dense layers
- Dropout (0.3)
- Sigmoid output (Binary classification)

## 📊 Results
Achieved ~85–90% validation accuracy on test dataset.

## ▶️ Run the Project

### 🔹 Open in Google Colab
[Open Notebook](https://colab.research.google.com/drive/1kF2vupgmeJyo3Ymev6C70KdjhKu2ZU9m?usp=sharing)

### 🔹 Dataset
Dataset is automatically downloaded using KaggleHub.

## 📌 Future Improvements
- Use transfer learning (VGG16 / ResNet)
- Increase epochs for better accuracy
- Add confusion matrix visualization
