# breast-cancer-segmentation-project

## Overview
Deep learning project for breast ultrasound image segmentation using U-Net. The model localizes pathological regions in ultrasound scans, achieving a validation Dice coefficient of ~0.74.  
It was adapted from a Kaggle dataset and trained/tested in a Jupyter Notebook environment.

## Dataset
- Dataset source: [Kaggle - Breast Ultrasound Images](/kaggle/input/breast-ultrasound-images-dataset)  
- Classes: Normal, Benign, Malignant  
- Includes segmentation masks for training.

## Methodology
- Preprocessing (resizing, normalization, augmentation)  
- Model: U-Net convolutional neural network  
- Training with Dice loss + cross-entropy  
- Evaluation using Dice coefficient and IoU  

## Results
- Validation Dice coefficient: **0.74**  
- Model shows strong performance in identifying malignant regions.  

## Tools Used
- Python  
- TensorFlow / Keras  
- NumPy, Pandas, Matplotlib  
