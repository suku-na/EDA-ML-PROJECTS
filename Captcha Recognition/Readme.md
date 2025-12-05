# 🔐 CAPTCHA Recognition using Deep Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange.svg)
![Status](https://img.shields.io/badge/Project-Active-brightgreen.svg)

This project focuses on building an automated CAPTCHA recognition system using Convolutional Neural Networks (CNNs).  
The goal is to train a deep learning model capable of reading text from CAPTCHA images and predicting the correct characters.

---

## 📌 Project Overview

CAPTCHAs are used to differentiate humans from bots. They are intentionally distorted to make automated reading difficult.

This project demonstrates:
- CAPTCHA image preprocessing  
- Label extraction & encoding  
- Designing a CNN architecture for OCR (Optical Character Recognition)  
- Training & validating the model  
- Predicting CAPTCHA text from unseen images  

It serves as a practical introduction to **computer vision**, **image classification**, and **OCR using deep learning**.

---

## 🎯 Objectives

- Build a deep learning model that identifies characters inside CAPTCHA images  
- Convert CAPTCHA labels into machine-readable format  
- Train a robust CNN model  
- Evaluate accuracy and generalization  
- Predict text for new CAPTCHA images  

---

## 📂 Dataset Description

Your dataset typically contains:
- CAPTCHA images (e.g., PNG/JPG)
- File names representing labels (e.g., `7gkP2.png`)
- Fixed-length or variable-length CAPTCHA text

---

##Repository Structure

```
📦 Captcha Recognition
├── captchas/                  # Dataset images
├── Captcha Recognition.ipynb  # Training notebook
├── model.h5                   # Saved trained model
├── requirements.txt           # Dependencies
└── README.md                  # Project documentation
```



