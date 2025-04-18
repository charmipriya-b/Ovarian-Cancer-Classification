# Ovarian Cancer Detection Using Deep Learning Models

This project aims to advance ovarian cancer detection by leveraging cutting-edge Artificial Intelligence (AI) and Deep Learning techniques. By integrating state-of-the-art models with a meticulously curated dataset, this research makes significant contributions to the intersection of healthcare and technology.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Project Description](#project-description)
- [Methodology](#methodology)
  - [Dataset: STRAMPN](#dataset-strampn)
  - [Deep Learning Models](#deep-learning-models)
  - [Data Augmentation](#data-augmentation)
  - [Evaluation Metrics](#evaluation-metrics)
- [Technical Stack](#technical-stack)
- [Challenges and Contributions](#challenges-and-contributions)
- [Clinical Impact](#clinical-impact)
- [Future Scope](#future-scope)
- [Conclusion](#conclusion)

---

## Project Overview

### Problem Statement
Ovarian cancer is often diagnosed in its later stages due to the subtlety of symptoms and lack of accessible detection systems. This project provides a solution using deep learning models trained on histopathological images to distinguish cancerous and non-cancerous tissues with high precision.

---

## Project Description

### Objective
To build a robust AI-based diagnostic tool for the early and accurate detection of ovarian cancer using deep transfer learning models trained on curated medical datasets.

---

## Methodology

### Dataset: STRAMPN
- Binary Classification: Cancerous vs. Non-cancerous tissues
- Supervised by experienced pathologists and gynecologists
- Created to address the scarcity of publicly available ovarian cancer data

### Deep Learning Models
Five transfer learning models were implemented:
- ResNet50: Highest accuracy – 98.49%
- EfficientNetB0 – 97.81%
- DenseNet121 – 96.34%
- VGG16 – 88.72%
- InceptionV3 – 86.93%

### Data Augmentation
To increase robustness and generalization:
- Rotation
- Scaling
- Horizontal/Vertical Flips
- Brightness Adjustments

### Evaluation Metrics
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---


## Technical Stack
- Programming Language: Python
- Libraries: TensorFlow, Keras, OpenCV, NumPy, Matplotlib
- IDEs: Jupyter Notebook, Google Colab
- Dataset: STRAMPN (curated dataset)

---

## Challenges and Contributions

### Challenges
- Lack of reliable ovarian cancer image datasets
- Model overfitting on small datasets
- Complex tissue differentiation in images

### Contributions
- STRAMPN Dataset creation
- High-accuracy cancer detection model
- Opens doors for further AI-medical research

---

## Clinical Impact
- Early and accurate diagnosis of ovarian cancer
- Reduces diagnostic delays
- Supports radiologists and pathologists with AI-powered predictions

---

## Future Scope
- Integration with hospital diagnostic systems
- Expansion to multi-class classification (stages of cancer)
- Mobile/Web application for medical professionals
- Real-time image analysis using cloud APIs

---

## Conclusion
This project demonstrates the successful use of deep transfer learning for ovarian cancer detection, achieving up to 98.49% accuracy. The STRAMPN dataset and trained models provide a valuable foundation for further healthcare innovations through AI.

---
