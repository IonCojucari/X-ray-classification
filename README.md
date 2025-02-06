# Chest X-Ray Classification Using Deep Learning

## 📊 Project Overview

This project focuses on classifying chest X-ray images into **Normal** and **Pneumonia** categories using a deep learning model. The dataset comes from the popular chest X-ray dataset hosted on Kaggle. The model leverages convolutional neural networks (CNNs) to analyze medical imaging data and assist in automated diagnosis.

## 🚀 Features
- Image preprocessing and augmentation for robust model training
- Deep learning model using PyTorch
- Random image selection and real-time prediction
- Visualization of predictions with annotated outputs

## 🗂️ Dataset Structure
```
├── train\
│   ├── NORMAL\
│   └── PNEUMONIA\
├── val\
│   ├── NORMAL\
│   └── PNEUMONIA\
└── test\
    ├── NORMAL\
    └── PNEUMONIA
```

## 📦 Requirements
- Python 3.x

Install the dependencies:
```bash
pip install -r requirements.txt
```

## 🔍 Results
The model predicts whether an X-ray image shows signs of pneumonia or is normal. Results are displayed with the image and its predicted label.

## 📝 License
This project is licensed under the MIT License.

