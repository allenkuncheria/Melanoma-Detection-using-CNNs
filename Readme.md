# Title
Melanoma Detection using CNNs

# Description
Melanoma is a type of skin cancer that can be deadly if not detected early and accounts for 75% of skin cancer deaths.

The goal of this deep learning project is to build a CNN based model which can evaluate images, accurately detect melanoma and alert dermatologists. Such a solution has the potential to reduce a lot of manual effort needed in diagnosis.

# Project Pipeline
The project is executed as per the following steps:
- Data Reading/Data Understanding
- Dataset Creation
- Dataset Visualisation
- Model 1: Building & Training
- Data Augmentation
- Model 2: Building & Training with Data Augmentation
- Class Distribution
- Handling Class Imbalance
- Model 3: Building & Training on Rectified Class Imbalance Data

# Results
The final CNN model, trained on rectified class imbalance data, has a training accuracy of 0.9579 and validation accuracy of 0.7253. However, it suffers from overfitting and requires additional hyperparameter tuning, regularization or additional training data for improving generalisability.