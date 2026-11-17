# Lung Disease Classification Using DenseNet-121

## Overview

This research investigates the use of deep learning for automated lung disease classification using chest X-ray images.

A pre-trained DenseNet-121 architecture is implemented using transfer learning to classify chest X-ray images into four categories:

- COVID-19
- Normal
- Pneumonia
- Tuberculosis (TB)

The study also investigates whether image enhancement techniques can improve the classification performance of the model.

## Research Objectives

- Develop a deep learning model for multi-class lung disease classification.
- Implement DenseNet-121 using transfer learning.
- Investigate the impact of image enhancement techniques on chest X-ray classification.
- Compare the classification performance obtained using original and enhanced images.

## Model Architecture

- **Architecture:** DenseNet-121
- **Pre-trained weights:** ImageNet
- **Input image size:** 224 × 224
- **Batch size:** 32
- **Number of classes:** 4
- **Feature extraction:** Global Average Pooling

## Experiments

The implementation includes experiments involving:

1. Original chest X-ray images (Baseline).
2. Histogram Equalisation (HE).
3. Contrast Limited Adaptive Histogram Equalisation (CLAHE).

Additional enhancement experiments and their findings will be documented as the research progresses.

## Dataset

The dataset contains 12,643 chest X-ray images distributed across four classes:

| Class | Number of images |
|---|---:|
| COVID-19 | 3,159 |
| Normal | 3,161 |
| Pneumonia | 3,162 |
| Tuberculosis | 3,161 |
| **Total** | **12,643** |

Dataset access and usage are subject to the original dataset's licensing and distribution conditions.

## Experimental Results

| Experiment | Test Accuracy |
|---|---:|
| Original images | 91.05% |
| Histogram Equalisation | 90.53% |
| CLAHE | 91.58% |

CLAHE achieved the highest test accuracy among these three experiments.

Further evaluation includes confusion matrices, precision, recall, F1-scores and qualitative analysis of classification predictions.

## Technologies Used

- Python
- TensorFlow and Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Repository Contents

- Jupyter Notebook: Model implementation and experiments.
- Results: Model evaluation and performance comparisons.
- Figures: Training curves, confusion matrices and prediction visualisations.
- Documentation: Research methodology and findings.
