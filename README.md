# 🧠 Brain Tumor Detection 

## 📌 Project Overview
This project is a Brain Tumor Detection system built using Deep Learning and Transfer Learning (VGG16). It classifies MRI brain images into four tumor categories and provides predictions with confidence scores.

The system uses a Flask backend and a simple HTML frontend where users can upload MRI images and get real-time predictions.



## 📊 Dataset Details
- Source: Kaggle Brain MRI Dataset
- Training Images: ~5500
- Testing Images: ~1200
- Classes:
  - Glioma Tumor
  - Meningioma Tumor
  - Pituitary Tumor
  - No Tumor 

### 📁 Dataset & 🤖 Model Download Link
https://drive.google.com/drive/folders/10hWvEbRIVJZbQ91bb0v_7tbzNtlnH9Fz?usp=sharing



## 🧠 Model Architecture
- Base Model: VGG16 (Transfer Learning)
- Framework: TensorFlow / Keras
- Fully connected custom classification layers added
- Activation function: Softmax (multi-class classification)
- Output: Tumor type + confidence score



## ⚙️ Tech Stack

###   Deep Learning
- Python
- TensorFlow / Keras
- VGG16 (Transfer Learning - ImageNet pretrained)
- NumPy
- Scikit-learn
- Matplotlib (for training visualization)

###  Training Environment
- Google Colab (model training)
- Kaggle Dataset (MRI brain images)

### 🌐 Backend
- Flask (Python web framework)
- Werkzeug (file handling)
- Keras model loading (.h5 format)

### 🎨 Frontend
- HTML5




