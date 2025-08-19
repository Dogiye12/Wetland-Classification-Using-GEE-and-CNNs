Wetland Classification Using GEE and CNNs
About

This project demonstrates wetland classification using synthetic satellite-like data. Features include spectral bands (RED, GREEN, NIR, SWIR) and indices (NDVI, NDWI). A Convolutional Neural Network (CNN) is applied to classify samples into water, wetland, or upland classes.

Dataset

File: wetland_synthetic_dataset.xlsx

Samples: 120+

Features: RED, GREEN, NIR, SWIR, NDVI, NDWI

Labels:

0 → Water

1 → Wetland

2 → Upland

Workflow

Data Simulation: Synthetic dataset generated to mimic GEE-exported spectral features.

Preprocessing: Normalize band values and indices.

Modeling: Train a CNN on tabular spectral data for classification.

Evaluation: Accuracy, confusion matrix, and loss curves.

Requirements
python>=3.8  
tensorflow>=2.9  
numpy  
pandas  
matplotlib  
scikit-learn  

Usage

Clone this repository

Install dependencies

Run the Python script to train the CNN

Evaluate results with accuracy and confusion matrix

python wetland_classification.py

Author

Amos Meremu Dogiye
Github: https://github.com/Dogiye12
