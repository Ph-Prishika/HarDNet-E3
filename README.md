# HarDNet-E3: Enhanced Shallow Feature Learning for Pediatric Renal Ultrasound Hydronephrosis Severity Classification

Official PyTorch implementation of **HarDNet-E3**, a modified HarDNet85 architecture for four-class pediatric hydronephrosis severity classification from renal ultrasound images.

HarDNet-E3 enhances the original HarDNet85 through:

- Structured shallow-to-deep skip connections
- Squeeze-and-Excitation (SE) feature recalibration
- Residual stabilization within each HarDBlock

These architectural improvements preserve fine anatomical boundaries and texture information that are often degraded in speckle-dominated ultrasound images, leading to more robust hydronephrosis severity classification.

---

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
| Batch Size | 32 |

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
