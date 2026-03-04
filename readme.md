# MalaDetect AI – Malaria Detection System

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)  
[![Flask](https://img.shields.io/badge/Flask-2.0+-green.svg)](https://flask.palletsprojects.com)  
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-orange.svg)](https://tensorflow.org)  
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  

An AI-powered web application for automated malaria detection in blood cell images using deep learning models. The system classifies microscopic blood smear images as either **Parasitized** (infected) or **Uninfected** (healthy) with high accuracy.

---

## 🎯 Project Overview

This Flask-based web application leverages convolutional neural networks to assist healthcare professionals in malaria diagnosis. The system provides instant analysis of blood cell images with confidence scores, supporting early detection and treatment decisions.

### Key Features

- **AI-Powered Detection:** MobileNet, VGG16, and Custom CNN models  
- **High Accuracy:** 92–93% accuracy on test datasets  
- **User-Friendly Interface:** Drag-and-drop image upload with real-time preview  
- **Model Comparison:** Performance metrics and detailed analysis  
- **Secure Authentication:** User registration and session management  
- **Responsive Design:** Modern UI with dark/light theme support  

---

## 🏗️ System Architecture

### Models Implemented

| Model         | Accuracy | Speed      | Use Case                |
|---------------|----------|-----------|------------------------|
| **MobileNet** | 93.1%    | Very Fast | Production deployment  |
| **Custom CNN**| 92.8%    | Fast      | Lightweight inference  |
| **VGG16**     | 85.2%    | Slower    | Research comparison    |

---

## 🐍 Virtual Environment Setup

To ensure dependency isolation and reproducibility, a Python virtual environment is used.

### 1. Create Environment

```bash
python3 -m venv env
