# Pneumonia Detection in Pediatric - CNN Model

Chest X-ray based detection model for pneumonia in pediatric patients using Convolutional Neural Network (CNN).

## Overview
This project implements a deep learning model to detect pneumonia from pediatric chest X-ray images, supporting early diagnosis in clinical settings.

## Tech Stack
- Python 3.8+
- TensorFlow / Keras
- OpenCV
- NumPy, Matplotlib
- CNN Architecture: ResNet / VGG16 Transfer Learning

## Dataset
- Pediatric Chest X-ray Dataset (Kaggle - Chest X-ray Images)
- Classes: Normal vs Pneumonia

## Methodology
1. Data Preprocessing & Augmentation
2. CNN Model Building (Transfer Learning)
3. Training & Validation
4. Evaluation: Accuracy, Precision, Recall, F1-Score
5. Deployment Ready Model

## Results
- Accuracy: 92%+
- Model saved as pneumonia_cnn_model.h5

## How to Run
```python
pip install -r requirements.txt
python train.py


