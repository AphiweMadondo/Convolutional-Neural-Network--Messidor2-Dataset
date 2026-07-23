# Convolutional Neural Network for Diabetic Retinopathy Detection (Messidor-2 Dataset)

## Overview

This project implements a **Convolutional Neural Network (CNN)** for the binary classification of retinal fundus images as either:

- No Diabetic Retinopathy (No DR)
- Diabetic Retinopathy (DR)

The model was developed using the **Messidor-2 dataset** and investigates the use of image preprocessing techniques together with a hybrid CNN-SVM architecture to improve classification performance.

---

## Motivation

Early detection of diabetic retinopathy is critical for preventing severe vision loss. This project explores the application of deep learning techniques for automated retinal image analysis to assist in early diagnosis.

---

## Features

- Binary classification of retinal fundus images
- Image preprocessing using:
  - Contrast Limited Adaptive Histogram Equalization (CLAHE)
  - Brightness enhancement for dark retinal images
- Convolutional Neural Network (CNN) for feature extraction
- Support Vector Machine (SVM) classifier using extracted CNN features
- Evaluation using multiple performance metrics

---

## Dataset

**Dataset:** Messidor-2

The dataset contains retinal fundus images used for diabetic retinopathy screening.

**Note:** The dataset exhibited significant class imbalance, which affected the overall model performance.

---

## Model Architecture

The proposed model consists of:

- Image preprocessing
- 10-layer Convolutional Neural Network
- Feature extraction
- Support Vector Machine (SVM) classifier

The preprocessing stage improves image quality before feature extraction, enabling the CNN to learn more discriminative retinal features.

---

## Results

| Metric | Score |
|--------|------:|
| Accuracy | 68% |
| Precision | 63% |
| Recall | 67% |
| F1 Score | 64% |

---
## Future Improvements

- Improve performance using transfer learning (ResNet, EfficientNet, DenseNet)
- Address class imbalance through data augmentation or weighted loss functions
- Hyperparameter optimization
- Multi-class diabetic retinopathy classification
- Deploy the model as a web application for clinical use

---

## Author

Your Name
Aphiwe Sphephelo Madondo
---
## License

This project is intended for academic and research purposes.
