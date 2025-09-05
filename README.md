# Medical CNN for Lung Disease Detection

## Overview
This repository contains two Convolutional Neural Network (CNN) models developed during my Bachelor's thesis (2025).  
The models are designed to classify chest X-ray images for pneumonia and related lung disease detection.

- **Binary CNN**: Classifies images as Pneumonia or Normal  
- **Multi-class CNN**: Classifies images as Normal, Viral Pneumonia, or Bacterial Pneumonia  

The trained models have been deployed on a web application to demonstrate their usability in a real-world context.  

## Dataset
- Publicly available chest X-ray dataset  
- Preprocessing: resizing, normalization, augmentation  
- Training, validation, and test splits  

## Methodology
- Architecture: convolutional and pooling layers with fully connected dense layers  
- Loss function: Categorical CrossEntropy  
- Optimizer: Adam  
- Evaluation metrics: accuracy, precision, recall, confusion matrix  

## Results
- **Binary CNN**: Accuracy ≈  93.63% (update with results)  
- **Multi-class CNN**: Accuracy ≈  93.91% (update with results)  

Visualizations such as training curves and confusion matrices are included in the notebooks.  

## Deployment
The models were deployed in a **web application** to allow end-users to upload chest X-ray images and receive predictions.  
This demonstrates the practical applicability of the system beyond research.  

## Tools and Libraries
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn  
- Flask / Django (for deployment)  

## Future Work
- Extend deployment with a more robust front-end  
- Integrate transfer learning with ResNet or DenseNet for improved accuracy  
- Add explainability features (e.g. Grad-CAM)  

## Author
**Bengrine Malik Zakaria**  
B.Sc. in Computer Science, University of Constantine 2 (2025)  
