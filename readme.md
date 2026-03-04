# MalaDetect AI - Malaria Detection System

An AI-powered web application for automated malaria detection in blood
cell images using deep learning models. The system classifies
microscopic blood smear images as either **Parasitized** (infected) or
**Uninfected** (healthy) with high accuracy.

------------------------------------------------------------------------

## 🎯 Project Overview

This Flask-based web application leverages convolutional neural networks
to assist healthcare professionals in malaria diagnosis. The system
provides instant analysis of blood cell images with confidence scores,
supporting early detection and treatment decisions.

------------------------------------------------------------------------

## ✨ Key Features

-   AI-Powered Detection (MobileNet, VGG16, Custom CNN)
-   92--93% accuracy on test datasets
-   Drag-and-drop image upload
-   Model comparison support
-   Secure authentication
-   Responsive modern UI

------------------------------------------------------------------------

## 🏗️ System Architecture

Frontend (HTML/CSS/JS)\
↓\
Flask Backend\
↓\
TensorFlow Models\
↓\
Prediction Results

------------------------------------------------------------------------

## 🚀 Installation

``` bash
git clone https://github.com/yourusername/malaria-detection.git
cd malaria-detection
python3 -m venv env
source env/bin/activate  # Linux/Mac
env\Scripts\activate   # Windows
pip install -r requirements.txt
python app.py
```

Open in browser:

    http://localhost:5000

------------------------------------------------------------------------

## 📊 Performance

-   MobileNet: 93.1% accuracy\
-   Custom CNN: 92.8% accuracy\
-   VGG16: 85.2% accuracy

True Positive Rate: 93.2%\
True Negative Rate: 92.8%

------------------------------------------------------------------------

## 🗂️ Project Structure

    malaria-detection/
    ├── app.py
    ├── Models/
    ├── templates/
    ├── static/
    ├── Dataset/
    ├── requirements.txt
    └── README.md

------------------------------------------------------------------------

## ⚠️ Medical Disclaimer

For research and educational purposes only. Always consult qualified
medical professionals for clinical diagnosis and treatment decisions.
