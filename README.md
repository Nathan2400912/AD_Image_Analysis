# CS506_final project

# Alzheimer's Disease MRI Classification Project

## Description of the Project
We want to develop a deep learning-based system to automatically classify different behaviors of Alzheimer's disease using brain MRI scans. 

## Goals
1. Build a machine learning model that can classify Alzheimer's disease stages from MRI scans with accuracy exceeding 90%
2. Develop a system that can process and analyze MRI scans
3. Generate attention maps highlighting the specific brain regions influencing the classification decision

## Data Collection
### Data Sources
1. Primary Dataset: Kaggle Alzheimer's MRI Dataset
   - Contains labeled MRI scans of brain
   - Multiple classes representing different behaviors of Alzheimer's
   - 6400 images across all classes
   

2. Supplementary Datasets:
   - ADNI (Alzheimer's Disease Neuroimaging Initiative) database
   - OASIS (Open Access Series of Imaging Studies)

### Collection Method
1. Direct download from Kaggle platform
2. Application for access to ADNI and OASIS databases
3. Data preprocessing pipeline:
   - Image standardization
   - Noise reduction
   - Normalization
   - Data augmentation through rotation, scaling, and intensity adjustments

## Modeling Approach
1. Primary Model:
   - Deep Learning using Convolutional Neural Networks (CNN)
   
2. Model Optimization:
   - Hyperparameter tuning 

## Data Visualization ( HMMM?? )
1. Pre-training Visualizations:
   - Sample MRI visualizations across different classes
   - Distribution plots of pixel intensities
   - Heat maps showing class distribution
   - Box plots of image statistics across classes

2. Model Analysis Visualizations:
   - Confusion matrix with interactive hover details
   - ROC curves and AUC scores for each class
   - Grad-CAM visualizations showing model focus areas
   - Interactive learning curves (training vs. validation)
   - t-SNE plots of learned feature representations
   - Feature maps from different CNN layers

## Test Plan
  Data Splitting Strategy:
   - Training set: 80% of total data
   - Testing set: 20% of total data
   - Within training set, 10% used for validation
   - Cross-validation
