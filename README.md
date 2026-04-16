# MedBone-AI-Bone-Fracture-Detection-System

## 📌 Overview
BoneNet is a deep learning-based system for automatic bone fracture detection and classification from X-ray images. It leverages multiple architectures including MobileNet, Wide ResNet, and a custom Convolutional Neural Network (CNN) to compare performance in terms of accuracy and efficiency, aiming to assist in fast and reliable medical diagnosis.

---

## 🚀 Features
- Binary classification: Fractured vs Non-fractured
- Multiple deep learning models implemented
- Image preprocessing and data augmentation
- Performance comparison across models
- Medical imaging application (X-ray analysis)

---

## 🧠 Models Used
- **MobileNet** – Lightweight and efficient, suitable for low-resource environments  
- **Wide ResNet** – Deep architecture with high accuracy and robustness  
- **Custom CNN** – Task-specific optimized neural network  

---

## 📂 Dataset
- X-ray images of bones  
- Classes:
  - Fractured
  - Non-fractured  
- Dataset split:
  - Training set
  - Validation set
  - Test set  

---

## ⚙️ Preprocessing
- Image resizing to fixed dimensions  
- Normalization (pixel values scaled to [0,1])  
- Data augmentation:
  - Rotation
  - Flipping
  - Zooming  

---

## 📊 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

## 📈 Results

| Model        | Training Accuracy | Validation Accuracy |
|--------------|-----------------|--------------------|
| MobileNet    | 90.06%          | 85.79%             |
| Custom CNN   | 98.86%          | 95.76%             |
| Wide ResNet  | 96.37%          | 93.75%             |

**Best Accuracy:** Custom CNN  
**Best Efficiency:** MobileNet  

---

## 🧮 Loss Function
- Cross-Entropy Loss  

---

## 🛠️ Tech Stack
- Python  
- TensorFlow / Keras or PyTorch  
- NumPy  
- OpenCV / PIL  
- Matplotlib  

---
