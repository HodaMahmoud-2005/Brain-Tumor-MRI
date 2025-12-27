# 🧠 Brain Tumor MRI Classification using CNN

This project focuses on classifying brain tumors from MRI images using a **Convolutional Neural Network (CNN)**.  
The model predicts one of four classes: **Glioma**, **Meningioma**, **Pituitary Tumor**, or **No Tumor**.

The project applies the complete deep learning pipeline including data preprocessing, data augmentation, model building, training, evaluation, and performance improvement techniques.  
The model achieved **91.84% accuracy** on the test dataset.

---

## 📊 Dataset Overview

The dataset used is the **Brain Tumor MRI Dataset** from Kaggle.

**Dataset Details:**
- Total Images: 7,023 MRI images
- Classes:
  - Glioma Tumor
  - Meningioma Tumor
  - Pituitary Tumor
  - No Tumor
- Data Split:
  - Training: ~80%
  - Testing: ~20%
- Image Size: Resized to 224 × 224

---

## 🧠 Model Architecture

The model is a custom CNN architecture consisting of:
- Convolutional layers with ReLU activation
- Batch Normalization
- Max Pooling
- Dropout & L2 Regularization
- Fully connected layers
- Softmax output layer for multi-class classification

---

## 🖼️ Sample MRI Images

Below are examples from the dataset:

![MRI Samples](image/Brain%20Tumor%20MRI.jpeg)



## 📈 Training & Evaluation Results

- **Test Accuracy:** 91.84%
- **Loss:** 0.6873
- **Optimizer:** Adam
- **Loss Function:** Categorical Cross-Entropy

### Confusion Matrix

![Confusion Matrix](image/Brain%20Tumor%20confusion_matrix.jpeg)

### Training History ![Training Accuracy & Loss](image/ِAccuracy_loss.jpeg)


## 🛠️ Data Preprocessing & Augmentation

The following steps were applied:
- Image resizing to 224 × 224
- Normalization (pixel values scaled to [0,1])
- Data augmentation:
  - Rotation
  - Zoom
  - Horizontal flip
  - Width & height shift
- Shuffling and batching using `ImageDataGenerator`

---

## 🚀 Getting Started

### Prerequisites

To run this project, you need:

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/HodaMahmoud-2005/Brain-Tumor-MRI.git

2. Install dependencies:
 ```bash
pip install tensorflow numpy matplotlib scikit-learn

## Authors
- [Basmala ElKady](https://github.com/Basmala-ElKady)
- [Menna Hossny](https://github.com/Mennatullah122)
- [Hoda Mahmoud](https://github.com/HodaMahmoud-2005)
- [Jana Hegazy](https://github.com/janahegazy)
- [Hany Ziad](https://github.com/hanyzead123)
