# 🌍 Satellite Image Classification (RSI-CB256)

[![Python](https://img.shields.io/badge/python-3.6+-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-orange.svg)](https://tensorflow.org)
[![Keras](https://img.shields.io/badge/Framework-Keras-red.svg)](https://keras.io)

---

## 📌 Overview
This project builds and compares **traditional machine learning models** and **deep learning models** for classifying high-resolution satellite images using the **RSI-CB256 dataset**.

The goal is to demonstrate how deep learning, particularly Convolutional Neural Networks (CNNs), outperforms traditional approaches in extracting spatial features from image data.

---

## 📊 Dataset
The project uses the **RSI-CB256 satellite image dataset**, which contains images from remote sensing systems and Google Maps.

- **Image Size:** 256 × 256 pixels  
- **Classes:** 4 categories (e.g. urban, agriculture, water, forest)  

---

## 🔄 Workflow
1. Load and preprocess satellite images  
2. Perform feature extraction for traditional ML models  
3. Train traditional models (SVM, Random Forest, Decision Tree)  
4. Train deep learning models (CNN, Feed-Forward Neural Network)  
5. Evaluate and compare model performance  

---

## 🤖 Models Implemented

### Traditional Machine Learning
- Support Vector Machine (SVM)  
- Random Forest (RF)  
- Decision Tree (DT)  

### Deep Learning
- Convolutional Neural Network (CNN)  
- Feed-Forward Neural Network (FNN)  

---

## 📈 Results
Deep learning models outperform traditional machine learning models due to their ability to automatically learn spatial hierarchies from image data.

> ✅ Replace this section with your actual results once available  
> (Accuracy, Precision, Recall, F1-score)

---

## 🛠️ Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 📁 Project Structure
``
├── dataset/
├── notebooks/
│   └── Main Project Implimentation Codes.ipynb
├── README.md
