README
An Explainable Few-Shot Swin Transformer Framework for PCOS Detection from Ovarian Ultrasound Images
Overview

This project presents an Explainable AI-based Few-Shot Learning framework for multiclass ovarian ultrasound image classification using the Swin Transformer architecture. The system is designed to classify ovarian ultrasound images into:

Normal
PCOS
Dominant Follicle

The proposed framework addresses the major challenge of limited labeled medical datasets by using Few-Shot Learning and Transfer Learning techniques. Grad-CAM++ visualization is integrated to provide explainable predictions and improve clinical interpretability.

Objectives
Develop an AI-based automated PCOS detection system.
Handle limited medical datasets using Few-Shot Learning.
Improve feature extraction using Swin Transformer.
Perform multiclass ovarian ultrasound classification.
Integrate Explainable AI using Grad-CAM++.
Reduce overfitting using data augmentation and transfer learning.
Dataset Information

Dataset: Ovarian Ultrasound Dataset

Classes:

Normal
PCOS
Dominant Follicle

Total Images: 301

Dataset Split:

Training: 70%
Validation: 15%
Testing: 15%
Technologies Used
Python
PyTorch
Swin Transformer
Few-Shot Learning
Transfer Learning
Grad-CAM++
OpenCV
NumPy
Matplotlib
Scikit-learn
Methodology
1. Data Preprocessing
Image resizing (224 × 224)
Normalization
RGB conversion
Noise reduction
Contrast enhancement
2. Data Augmentation
Rotation
Horizontal flipping
Vertical flipping
Brightness adjustment
Zooming and translation
3. Feature Extraction
Swin Transformer architecture
Patch embedding
Window-based self-attention
4. Few-Shot Learning
5-shot
10-shot
20-shot
30-shot
40-shot
5. Classification
Multiclass classification
SoftMax activation
Cross-entropy loss
6. Explainable AI
Grad-CAM++
Heatmap visualization
Overlay generation
Performance Results
Shot Setting	Accuracy
5-Shot	77.42%
10-Shot	85.48%
20-Shot	87.10%
30-Shot	90.32%
40-Shot	95.16%
Performance Metrics

The model performance was evaluated using:

Accuracy
Precision
Recall
F1-Score
ROC Curve
Confusion Matrix
Advantages
Works effectively with limited medical data.
Provides explainable predictions using Grad-CAM++.
Reduces overfitting through augmentation.
Supports reliable clinical decision-making.
Scalable for future medical imaging applications.
Future Enhancements
Real-time clinical deployment.
Larger ovarian ultrasound datasets.
Integration with hospital diagnostic systems.
Hybrid CNN-Transformer architectures.
Self-supervised learning approaches.
Conclusion

The proposed Few-Shot Swin Transformer framework successfully performs multiclass ovarian ultrasound image classification under limited data conditions. The integration of Explainable AI improves transparency and reliability, making the system more suitable for real-world healthcare applications.