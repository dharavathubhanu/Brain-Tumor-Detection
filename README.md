**Brain Tumor Detection using Deep Learning**

This project implements a deep learning pipeline for brain tumor detection using MRI scan images. The primary objective is to classify MRI images into tumor and non-tumor categories using convolutional neural networks (CNN), along with comparisons against pre-trained models like VGG16 and MobileNetV2.

**Dataset**

The dataset used in this project is the "Brain Tumor MRI Dataset" from Kaggle. It contains MRI images categorized into:

Glioma

Meningioma

Pituitary tumor

No tumor

Folder Structure:

/brain-tumor-dataset/

/Training/

/Testing/

**Models Implemented**

CNN Model (from scratch)

VGG16 (Transfer Learning)

MobileNetV2 (Transfer Learning)

**Results**

Model	Accuracy
CNN (Simple)	80.39%
VGG16	84.17%
MobileNetV2	84.31% (best)

MobileNetV2 gave the best performance, balancing accuracy and computational efficiency.

**Performance Evaluation**

Confusion Matrix

Accuracy Score

Precision, Recall, F1-Score

Training/Validation Curves

**Future Work**

Multi-class tumor classification

3D MRI analysis

Integration into a web or mobile app

Explainable AI (XAI) integration

**Author**

Bhanu Prasad Dharavathu

