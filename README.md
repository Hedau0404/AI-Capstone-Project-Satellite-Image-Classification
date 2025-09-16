# AI-Capstone-Project-Satellite-Image-Classification
AI Capstone Project: Deep learning models for classifying agricultural vs non-agricultural land using satellite images (Keras, PyTorch, Vision Transformers).

# 🌍 AI Capstone Project – Satellite Image Classification

**Course:** IBM AI Engineering Capstone (Coursera)  
**Author:** Prathamesh Hedau

**Tools & Frameworks:** Python, Jupyter, Keras, PyTorch, Vision Transformers  

---

## 📌 Project Overview
This project is part of the **IBM AI Engineering Professional Certificate** on Coursera.  
The goal is to build and compare **deep learning models** that classify satellite images into two categories:  

- **Class 0:** Non-agricultural land  
- **Class 1:** Agricultural land  

The project simulates a real-world use case: a fertilizer company wants to automatically classify land types to support **territory expansion, climate monitoring, and agricultural planning**.  

---

## 🧩 Project Modules

### 🔹 Module 1: Data Preparation & Exploration
- Loaded and explored satellite images efficiently.  
- Preprocessed data with resizing (64×64) and augmentation.  
- Balanced datasets for training and testing.  

### 🔹 Module 2: Building & Comparing Basic Classifiers
- Implemented **Convolutional Neural Networks (CNNs)** in:
  - **Keras (TensorFlow backend)** – beginner-friendly, high-level API.  
  - **PyTorch** – more flexible, low-level control.  
- Compared performance using accuracy, precision, recall, and confusion matrices.  
- Achieved **>95% accuracy** on classification tasks.  

### 🔹 Module 3: Advanced Models – Vision Transformers (ViTs)
- Introduced **Vision Transformers (ViTs)** for image classification.  
- Built **CNN–ViT hybrid models** to leverage:
  - CNNs → local feature extraction.  
  - ViTs → global context and attention.  
- Used **transfer learning** to improve accuracy with fewer resources.  

### 🔹 Module 4: Integration & Final Evaluation
- Combined models for better performance.  
- Tackled **overfitting** with dropout and augmentation.  
- Evaluated with cross-validation and real-world test sets.  

---

## 🚀 Key Results
- CNN classifiers reached **>95% accuracy**.  
- ViTs improved **generalization on complex patterns**.  
- CNN–ViT hybrids provided the **best balance of speed and accuracy**.  

---

## 📊 Applications
- Agriculture & fertilizer industry expansion.  
- Climate and environmental monitoring.  
- Urban planning & disaster response.  
- Smart farming technologies.  

---

## ⚡ How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/Hedau0404/AI-Capstone-Project-Satellite-Image-Classification.git
