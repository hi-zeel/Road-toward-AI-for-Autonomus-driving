# 🧠 From Scratch to CNNs: My Neural Network Learning Journey

This repository documents my **hands-on journey** of learning Neural Networks and Convolutional Neural Networks (CNNs) step by step.  
The motivation was to build strong foundations in AI to complement my **Autonomous Vehicle (ADAS)** research.

---

## 📌 Motivation
Autonomous vehicles rely heavily on **computer vision** — from detecting traffic signs 🚦 to recognizing pedestrians.  
To master this, I started from scratch with neural networks and worked my way up to CNNs, autoencoders, and transfer learning.

This repo contains **6 projects**, each representing a milestone in my learning path.

---

## 🚀 Contents

### 1. Neural Networks from Scratch
**File:** `Neural_Network.ipynb`  
- Introduces the concept of **artificial neurons** and how stacking them creates powerful function approximators.  
- Implemented a simple neural net using only **NumPy**.  

**Key Idea:** Like Lego blocks — each unit is simple, but together they form complex structures.  

---

### 2. Convolutional Neural Networks (CNNs)
**File:** `CNNs.ipynb`  
- Step-by-step breakdown of CNN components: **convolutions, kernels, pooling, fully-connected layers**.  
- Demonstrates why CNNs are so effective for vision: *locality, translation invariance, parameter sharing*.  

Sample filter visualization:  
{image_tags['CNNs.ipynb'][0] if image_tags['CNNs.ipynb'] else ''}

---

### 3. MNIST Digit Recognition
**File:** `Number_recognition_CNN.ipynb`  
- Classic **digit recognition task** using CNNs on the MNIST dataset.  
- Achieved strong accuracy with a relatively shallow CNN.  

Example classification results:  
{image_tags['Number_recognition_CNN.ipynb'][0] if image_tags['Number_recognition_CNN.ipynb'] else ''}

---

### 4. Fashion-MNIST Autoencoder (Image Denoising)
**File:** `Fashion_MNIST_Autoencoder.ipynb`  
- Built an **encoder-decoder network** to remove Gaussian noise from clothing images.  
- Demonstrates the power of **representation learning**.  

Noisy vs. reconstructed images:  
{image_tags['Fashion_MNIST_Autoencoder.ipynb'][0] if image_tags['Fashion_MNIST_Autoencoder.ipynb'] else ''}

---

### 5. Traffic Sign Recognition (ADAS Link 🚦)
**File:** `Traffic_sign_CNN.ipynb`  
- Trained CNN on **German Traffic Sign Recognition Benchmark (GTSRB)**.  
- Added **Grad-CAM** visualizations to see *where the network is looking*.  
- Directly connected to autonomous driving perception systems.  

Feature map visualization:  
{image_tags['Traffic_sign_CNN.ipynb'][0] if image_tags['Traffic_sign_CNN.ipynb'] else ''}

Grad-CAM heatmap on traffic signs:  
{image_tags['Traffic_sign_CNN.ipynb'][1] if len(image_tags['Traffic_sign_CNN.ipynb']) > 1 else ''}

---

### 6. CIFAR-10: Scratch CNN vs. ResNet18 (Transfer Learning)
**File:** `CFIFAR-10.ipynb`  
- Compared a **custom CNN (~75% accuracy)** with a **pretrained ResNet18 (~90% accuracy)**.  
- Highlights the value of **transfer learning** for small datasets.  

Performance comparison:  
{image_tags['CFIFAR-10.ipynb'][0] if image_tags['CFIFAR-10.ipynb'] else ''}

---

## 📈 Skills Demonstrated
- Neural networks implementation from scratch
- CNN architecture design and visualization
- Autoencoders for denoising
- Transfer learning with pretrained models
- Computer Vision for ADAS applications
- Model interpretability with Grad-CAM

---

## 🛠️ Tech Stack
- **Python** (NumPy, PyTorch)
- **Jupyter Notebooks**
- **Datasets**: MNIST, Fashion-MNIST, GTSRB, CIFAR-10

---

## 🌟 Why This Matters
This journey built the foundation I now apply in **Autonomous Vehicle AI projects**.  
For example, traffic sign recognition is a crucial ADAS feature.  
The ability to implement, train, and interpret models ensures both **accuracy and safety**.

---
