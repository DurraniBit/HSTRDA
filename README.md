# RDA-Net for motor imagery EEG classification
### RDA-Net: Riemannian Domain-Adaptive Network for EEG Motor Imagery Classification

RDA-Net is a unified deep learning framework designed for robust and generalizable EEG-based motor imagery (MI) classification. It integrates Riemannian geometry, convolutional feature extraction, sparse Transformers, and adversarial domain adaptation to achieve state-of-the-art performance on cross-subject EEG datasets.

Key features include:
- **Riemannian Geometry Layer:** Dual-regularized Log-Cholesky embeddings for stable and discriminative spatial covariance features from SPD matrices.
- **Lightweight CNN Backbone:** Efficient extraction of localized spatio-temporal EEG patterns.
- **Adaptive Feature Fusion Module:** Aligns and projects Riemannian and CNN features into a unified space with positional encoding, enabling token-level cross-branch interactions.
- **Sparse Transformer Encoder:** Captures long-range temporal dependencies with linear complexity.
- **Adversarial Domain Adaptation:** Gradient Reversal Layer to learn domain-invariant representations across subjects.

RDA-Net has been validated on **BCI Competition IV-2a, IV-2b, and High Gamma datasets**, achieving superior classification accuracy in both subject-dependent and cross-subject settings.

This repository provides:
- Training and evaluation scripts for standard BCI datasets
- Preprocessing pipelines for EEG covariance computation
- Pre-trained model weights for benchmark datasets
- Utilities for visualization (t-SNE, Grad-CAM) and performance analysis

Our research builds upon and improves the [EEG Conformer](https://github.com/eeyhsong/EEG-Conformer) and [RGN](https://github.com/shiroger/Riemannian-Geometry-Networks), and we sincerely thank the creators of these open-source project.


### Abstract:


### Overall Framework:
![architecture of RDA-Net](main/architecture.png)

### Requirements:
Python 3.10

Pytorch 1.13.1


### Citation
Hope this code can be useful. I would appreciate you citing us in your paper. 😊


