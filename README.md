# Road Toward AI for Autonomous Driving 🚗🤖

This repository captures my step-by-step journey into **Deep Learning for Autonomous Driving**.  
Starting from toy datasets, I gradually built up my skills in Convolutional Neural Networks (CNNs)  
and applied them to real-world perception tasks like **traffic sign recognition**.

---

## 📘 Step 1 – Fashion-MNIST: Learning the Basics
Notebook: [`Fashion_CNN.ipynb`](./Fashion_CNN.ipynb)

- First hands-on CNN implementation.  
- Learned about **convolutions, pooling, and fully connected layers**.  
- Classified clothing items in the **Fashion-MNIST** dataset.  
- Gained intuition about how CNNs extract features from raw pixels.

👉 *This stage gave me the foundation to apply CNNs beyond simple examples.*

---

## 📗 Step 2 – Number Recognition (MNIST)
Notebook: [`Number_recognition_CNN.ipynb`](./Number_recognition_CNN.ipynb)

- Extended CNN knowledge to **digit classification** with the classic **MNIST dataset**.  
- Focused on:
  - Training deeper networks.
  - Handling larger training data efficiently.
  - Improving accuracy with better hyperparameters.  
- Digits connect directly to **autonomous driving use-cases** (e.g., speed limits, road numbers).

👉 *Here I started connecting CNN skills with perception tasks needed in self-driving.*

---

## 📕 Step 3 – Traffic Sign Recognition (GTSRB)
Notebook: [`Traffic_sign_CNN.ipynb`](./Traffic_sign_CNN.ipynb)

- Final milestone: **German Traffic Sign Recognition Benchmark (GTSRB)**.  
- Built a CNN capable of classifying road signs — a **core ADAS task**.  
- Introduced:
  - **Feature maps** for visualizing learned filters.  
  - **Grad-CAM** for model interpretability (seeing *where* the CNN looks).  

👉 *This stage directly ties deep learning to **autonomous driving perception systems.***

---

## 🌱 Reflection – From Pixels to Roads
- Began with toy datasets to learn **how CNNs work**.  
- Progressed to **digits**, connecting to driving-relevant numbers.  
- Reached **traffic signs**, aligning with **real-world autonomous driving needs**.  

This progression shows not just technical learning, but also a **clear roadmap toward AI in self-driving vehicles**.

---

## 📂 Repository Structure
- `Fashion_CNN.ipynb` → First CNN (Fashion-MNIST).  
- `Number_recognition_CNN.ipynb` → Digits with CNN (MNIST).  
- `Traffic_sign_CNN.ipynb` → Traffic signs with CNN + feature maps + Grad-CAM (GTSRB).  
