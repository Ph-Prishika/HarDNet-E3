# HarDNet-E2
### Enhanced Shallow Feature Learning for Pediatric Renal Ultrasound Hydronephrosis Classification

HarDNet-E2 is a modified HarDNet85 architecture designed for pediatric renal ultrasound image classification. The network enhances shallow feature propagation through structured shallow-to-deep skip connections, even-layer feature aggregation, squeeze-and-excitation (SE) feature recalibration, and residual feature fusion. These modifications improve the preservation of fine anatomical structures and boundary information in speckle-dominated ultrasound images.

This repository provides the official PyTorch implementation of HarDNet-E2, including training, evaluation, calibration, explainability, and visualization tools for reproducible medical image classification experiments.

---

## Key Features

- Enhanced shallow-to-deep feature reinforcement
- Even-layer feature aggregation within HarDBlocks
- Squeeze-and-Excitation (SE) feature recalibration
- Residual feature fusion
- Patient-level data splitting to prevent image leakage
- Confidence calibration analysis (ECE)
- Bootstrap statistical significance testing
- Grad-CAM visualization
- ROC and Precision–Recall curve generation
- Frequency-domain feature analysis
- Speckle-noise robustness evaluation

---

## Problem Setting

Classification of pediatric renal ultrasound images into:

- **Healthy**
- **Mild Hydronephrosis**
- **Moderate Hydronephrosis**
- **Severe Hydronephrosis**

**Input:** ROI-cropped renal ultrasound images (224 × 224)

---

## Architecture Overview

HarDNet-E2 extends the original HarDNet85 by introducing:

- Structured shallow-to-deep feature reinforcement
- Even-layer feature aggregation within HarDBlocks
- Squeeze-and-Excitation (SE) channel attention
- Residual feature fusion for stable optimization

## Features

- Four-class hydronephrosis severity classification
  - Healthy
  - Mild
  - Moderate
  - Severe
- Patient-level data splitting to prevent data leakage
- Multi-vendor renal ultrasound evaluation
- ROC and Precision–Recall analysis
- Frequency-domain feature analysis
- Speckle-noise robustness evaluation
- Confidence calibration analysis
- Grad-CAM visualization
- Ablation studies

---


## Hardware

| Component | Specification |
|-----------|---------------|
| GPU | 2 × NVIDIA GeForce RTX 2080 Ti |
| VRAM | 11 GB per GPU |
| CUDA | 12.7 |
| Framework | PyTorch |
| Input Size | 224 × 224 |
| Batch Size | 16 |

---


## Repository Includes

- HarDNet-E3 architecture
- Training and evaluation scripts
- ROC and Precision–Recall curve generation
- Confusion matrix generation
- Frequency-domain analysis
- Speckle-noise robustness evaluation
- Confidence calibration
- Grad-CAM visualization

---



## License

This repository is intended for academic and research use.
