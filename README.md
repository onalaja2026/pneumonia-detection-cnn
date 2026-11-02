# Pneumonia Detection Using CNN - Chest X-ray Analysis

AI in Healthcare Research Project - Pediatric Pneumonia Detection

## Overview
Deep learning model for automated detection of pneumonia in pediatric chest X-ray images using Convolutional Neural Networks (CNN). Aims to assist radiologists in early diagnosis, especially in resource-limited settings.

## Problem Statement
Pneumonia is a leading cause of child mortality in Nigeria. Manual X-ray interpretation is time-consuming and requires expert radiologists. This project automates detection with AI.

## Tech Stack
- Language: Python
- Deep Learning: TensorFlow, Keras
- Model: Convolutional Neural Network (CNN) - ResNet50 / Custom CNN
- Dataset: Chest X-ray Images (Pediatric) - Kermany et al.
- Libraries: NumPy, Pandas, Matplotlib, Scikit-learn, OpenCV

## Methodology
1. Data Preprocessing: Resizing (224x224), Normalization, Augmentation
2. Model Architecture: CNN with Transfer Learning (ResNet50)
3. Training: 80% train, 20% test, EarlyStopping, Adam optimizer
4. Evaluation: Accuracy, Precision, Recall, F1-Score, Confusion Matrix, Grad-CAM visualization

## Results (Expected)
- Target Accuracy: >90%
- Model able to distinguish Normal vs Pneumonia with high sensitivity

## Features
- Automated chest X-ray classification
- Explainable AI with Grad-CAM heatmaps
- Web deployment ready (Flask API)

## Research Contribution
Contributes to AI in Healthcare research, demonstrating applicability of CNN in medical image analysis for low-resource environments like Nigeria.

## Future Work
- Extend to multi-class (Bacterial vs Viral pneumonia)
- Deploy as mobile health application

## Author
*Olabisi Onalaja*
Computer Science Lecturer / PhD Researcher
AI in Healthcare & Agricultural Tech | Python, ML, CNN
olabisionalaja07@gmail.com
GitHub: @onalaja2026

## Reference
Kermany et al., Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification.


