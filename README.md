# Liver Fibrosis Classification Using Deep Learning and Hybrid Architectures

A deep learning-based medical image analysis project for multi-class liver fibrosis classification from ultrasound images, featuring comparative model evaluation, hybrid architectures, explainable AI, model calibration, and comprehensive experimental analysis.

## Overview

Liver fibrosis is a progressive condition characterized by the accumulation of scar tissue in the liver. Accurate assessment of fibrosis stages is important for understanding disease progression.

This project investigates deep learning and hybrid architectures for classifying liver ultrasound images into five fibrosis stages (F0–F4).

The research explores CNN-based models, Vision Transformers, and hybrid feature extraction approaches, along with explainability and calibration techniques to evaluate model performance, interpretability, and prediction reliability.

## Classification Categories

| Stage | Description |
|---|---|
| F0 | No Fibrosis |
| F1 | Portal Fibrosis |
| F2 | Few Septa |
| F3 | Many Septa |
| F4 | Cirrhosis |

## Deep Learning Architectures

### CNN-Based Architectures
- ResNet50
- DenseNet121
- EfficientNet-B3

### Transformer-Based Architectures
- Vision Transformer (ViT-B/16)
- Swin Transformer

### Hybrid Architecture
- A hybrid architecture combining Swin Transformer with CNN-based feature extraction for complementary feature representation.

## Research Contributions and Experimental Analysis

### 1. Comparative Model Evaluation
Comparative investigation of CNN, Transformer, and hybrid architectures for five-class liver fibrosis classification.

### 2. Hybrid Architecture
Exploration of combined CNN and Transformer feature representations to leverage complementary feature-learning capabilities.

### 3. Sensitivity and Specificity Analysis
Evaluation of the models' ability to identify positive and negative cases across fibrosis stages.

### 4. Ablation Study
Investigation of the contribution of individual model components to overall classification performance.

### 5. Error Analysis
Examination of misclassified samples and challenging cases to understand model limitations and potential sources of prediction errors.

### 6. Explainable AI Using Grad-CAM
Application of Gradient-weighted Class Activation Mapping (Grad-CAM) to visualize important image regions influencing model predictions.

### 7. Model Calibration and Reliability
Evaluation of prediction confidence and calibration using:
- Expected Calibration Error (ECE)
- Brier Score

## Evaluation Metrics

The experimental evaluation includes:

- Accuracy
- Precision
- Recall
- Sensitivity
- Specificity
- F1-score
- Confusion Matrix
- ROC-AUC (where evaluated)
- Expected Calibration Error (ECE)
- Brier Score

## Experimental Workflow

1. Dataset preparation
2. Ultrasound image preprocessing
3. CNN and Transformer model implementation
4. Model training and validation
5. Hybrid architecture development
6. Comparative performance evaluation
7. Sensitivity and specificity analysis
8. Ablation study
9. Error analysis
10. Grad-CAM visualization
11. Calibration analysis using ECE and Brier Score

## Technologies Used

- Python
- Google Colab
- TensorFlow / Keras
- PyTorch (if used)
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- OpenCV

## Repository Structure

```text
Liver-Fibrosis-Classification/
│
├── Liver_Fibrosis_The_Project.ipynb
├── README.md
│
└── results/
    ├── confusion_matrix.png
    ├── training_curves.png
    ├── performance_comparison.png
    ├── ablation_study.png
    ├── calibration_analysis.png
    ├── error_analysis/
    └── gradcam/
```

*The results directory will be populated with actual experimental outputs.*

## How to Run

1. Open the notebook using Google Colab.
2. Configure the dataset path.
3. Install the required dependencies.
4. Execute the notebook cells sequentially.
5. Review the model training, evaluation, and visualization outputs.

## Dataset

The dataset is not included in this repository. Users must obtain the dataset separately and follow its licensing and usage requirements.

## Future Research Directions

- Further optimization of hybrid architectures.
- Improved generalization across ultrasound datasets.
- More comprehensive explainability and calibration analysis.
- Computational efficiency and inference-time optimization.

## Disclaimer

This project is intended for academic and research purposes only. It is not a clinically validated diagnostic system and should not replace professional medical advice.

## Author

**Himadree Chowdhury**

GitHub: [HimadreeChy](https://github.com/HimadreeChy)
