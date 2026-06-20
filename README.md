# Blur-Aware-Transformer-Based-Monocular-Depth-Estimation
Transformer-based monocular depth estimation system using Swin Transformer, multi-scale skip decoder, and NYU Depth V2 dataset.
# Prism AI: Blur-Aware Transformer-Based Monocular Depth Estimation

## Overview

Prism AI is a transformer-based monocular depth estimation system designed to predict dense depth maps from a single RGB image.

The project explores multiple depth estimation architectures and evaluates their performance using the NYU Depth V2 dataset and KITTI benchmark dataset.

The final model uses a Swin Transformer backbone with a custom multi-scale skip decoder for dense depth prediction.

---

## Features

- Swin Transformer Backbone
- Multi-Scale Skip Decoder
- Edge-Aware Loss Function
- Monocular Depth Estimation
- NYU Depth V2 Training
- KITTI Generalization Evaluation
- Real-World Scene Testing

---

## Architecture

RGB Image
↓
Swin Transformer
↓
Multi-Scale Feature Extraction
↓
Skip Connections
↓
Custom Decoder
↓
Dense Depth Map

---

## Datasets

### NYU Depth V2
Indoor RGB-D dataset used for training and validation.

### KITTI
Outdoor autonomous driving dataset used for generalization testing.

---

## Experimental Results

| Model | Validation Loss |
|---------|---------|
| V1 | 0.4183 |
| V2 | 0.4359 |
| V3 | 0.4161 |
| V3 Final | **0.40896** |

### Final Metrics

| Metric | Value |
|---------|---------|
| MAE | 0.4269 |
| RMSE | 0.6339 |
| Parameters | 34,528,027 |

---

## Technologies Used

- Python
- PyTorch
- Swin Transformer
- timm
- OpenCV
- NumPy
- Matplotlib
- Google Colab

---

## Repository Contents

- Training Notebook
- Experimental Results
- Evaluation Pipeline
- Depth Prediction System

---

## Author

Ojaswi Singh
