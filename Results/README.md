# Experimental Results

This directory contains the evaluation results and visual outputs obtained from the lung disease classification experiments using DenseNet-121 with transfer learning.

## Experiments

The results are organised according to three experimental conditions:

1. **Baseline:** Classification using original chest X-ray images.
2. **Histogram Equalization (HE):** Classification using histogram-equalized images.
3. **CLAHE:** Classification using Contrast Limited Adaptive Histogram Equalization.

## Directory Structure

- `confusion_matrices/`: Confusion matrices generated for each experiment.
- `classification_reports/`: Classification reports containing precision, recall, F1-score and support.
- `predictions/`: Saved model predictions on test images.
- `visual_comparisons/`: Visual comparisons of original and enhanced chest X-ray images.

## Overall Test Accuracy

| Experiment | Accuracy |
|---|---:|
| Baseline | 91.05% |
| Histogram Equalization | 90.53% |
| CLAHE | 91.58% |

CLAHE achieved the highest test accuracy among the three experimental conditions.
