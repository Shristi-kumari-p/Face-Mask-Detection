# 😷 Face Mask Detection using CNN

## 📌 Project Overview

During and after the COVID-19 pandemic, organizations such as hospitals, airports, offices, shopping malls, and other public spaces needed automated solutions to monitor whether people were wearing face masks.

Manual monitoring is time-consuming and can be prone to human error. This project develops a **Deep Learning-based Computer Vision model using Convolutional Neural Networks (CNN)** to automatically classify face images into two categories:

- 😷 **With Mask**
- 🚫 **Without Mask**

The trained model can serve as a foundation for future integration with **webcam or CCTV-based real-time monitoring systems**.

---

## 🎯 Problem Statement

Manual monitoring of face-mask usage in crowded environments is difficult, time-consuming, and not always reliable.

The goal of this project is to develop a computer vision model that can automatically determine whether a person is wearing a face mask or not from an input face image.

---

## 🎯 Objectives

The main objective is to classify an input face image into one of two categories:

1. **With Mask**
2. **Without Mask**

The project also aims to demonstrate how CNN-based deep learning can be applied to image classification and computer vision problems.

---

## 🧠 Approach

The project follows the following workflow:

```text
Face Mask Dataset
       ↓
Data Loading
       ↓
Image Preprocessing
       ↓
Image Augmentation
       ↓
CNN Model Development
       ↓
Model Training
       ↓
Validation
       ↓
Model Evaluation
       ↓
Mask / No Mask Prediction

🛠️ Technologies Used
Python
TensorFlow
Keras
NumPy
Pandas
Matplotlib
Scikit-learn
Jupyter Notebook
Convolutional Neural Network (CNN)
Computer Vision

## 📊 Model Evaluation

The final CNN model was evaluated on **991 unseen test images**.

### Performance Summary

|         Metric       |    Score   |
|----------------------|------------|
|   Test Accuracy      | **98.49%** |
|   Test Loss          | **0.0583** |
|   Mask F1-Score      |  **99%**   |
|   No Mask F1-Score   |  **98%**   |
|  Correct Predictions | **976/991**|
| Misclassified Images | **15/991** |

🚀 Future Scope

The current project focuses on classifying individual face images. The solution can be further enhanced by:

Integrating the model with webcam feeds
Integrating the model with CCTV/video streams
Implementing real-time face detection
Combining face detection with mask classification
Deploying the model as a web application
Optimizing the model for edge devices
Building a complete real-time monitoring system

✅ Conclusion

This project successfully demonstrates the application of Convolutional Neural Networks (CNNs) and Computer Vision for automated face-mask detection.

The final model achieved a 98.49% accuracy on 991 unseen test images, correctly classifying 976 images with only 15 misclassifications. It achieved an F1-score of 99% for the Mask class and 98% for the No Mask class, demonstrating strong and balanced classification performance.

The results show that CNN-based deep learning can effectively distinguish between masked and unmasked faces. The developed model can serve as a strong foundation for future webcam and CCTV-based near real-time face-mask monitoring systems.
