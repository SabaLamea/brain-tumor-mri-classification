# 🧠 Brain Tumor MRI Classification – Graduation Project 🎓

This project aims to classify brain tumors using deep learning models on MRI scans. It detects and categorizes images into four types: **Glioma**, **Meningioma**, **Pituitary**, or **No Tumor**. The dataset is sourced from Kaggle and contains high-resolution images in a structured format.

## 📊 Dataset
- **Source:** [Brain Tumor MRI Dataset – Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- **Classes:**
  - Glioma Tumor
  - Meningioma Tumor
  - Pituitary Tumor
  - No Tumor
- **Total Images:** 7022 (approx.)

## 📌 Project Highlights

### 🔬 1. Preprocessing
- Image resizing, normalization, and augmentation
- Class-wise balanced train-test split
- Data generators for each model

### 🤖 2. Models Implemented
- ✅ Custom CNN (from scratch)
- ✅ MobileNetV2
- ✅ ResNet50
- ✅ VGG16
- ✅ DenseNet121

### 📈 3. Evaluation Results

#### 🧠 CNN (Custom)
- **Accuracy:** 0.95
- **F1 Score:** 0.95
- **Best Recall:** Glioma (1.00)

#### 📱 MobileNetV2
- **Accuracy:** 0.906
- **Precision:** 0.912
- **Recall:** 0.906
- **F1 Score:** 0.904

#### 🔍 ResNet50
- **Accuracy:** 0.95
- **F1 Score:** 0.95
- **Notable Strength:** Very high recall on Pituitary & No Tumor

#### 🧠 VGG16
- **Accuracy:** 0.9786
- **Precision/Recall/F1:** ≈ 0.9786

> 📌 **Best Performing Model:** VGG16 with ~97.8% accuracy

### 💻 4. Deployment
The project is deployed as a **web application using Streamlit** for interactive prediction and model selection. The frontend interface is styled using:
- **HTML**
- **CSS**
- **JavaScript**

Users can upload MRI scans and choose a model to classify the image with real-time confidence output.

## 🚀 How to Use
1. Clone the repository
2. Run the Streamlit app:
   ```bash
   streamlit run app.py
