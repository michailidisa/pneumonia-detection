# pneumonia-detection

# Pneumonia 3-Class Classification

The code used for my submissions, achieved a 86.84% accuracy on Private Results ranking 2nd in the in-class Kaggle competition

## Goal

The goal was to classify chest x-ray images into 3 classes:

- healthy
- bacterial pneumonia
- viral pneumonia

## Dataset

The training dataset consisted of 4672 images out of which:

1227 images belong to healthy subjects
2238 images belong to bacterial pneumonia subjects
1207 images belong to viral pneumonia subjects

## Sumbission

The submissions employed:

- Data Transformation
- Data augmentation
- Transfer learning with EfficientNet and ImageNet models, trained on ImageNet
- Softmax ensemble of 16 models for final predictions
