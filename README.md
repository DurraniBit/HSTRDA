# HSTRDA for motor imagery EEG classification
### HSTRDA:  Hybrid Spatio-temporal Riemannian Domain Adaptation Scheme for Improved Motor Imagery Classification




Our research builds upon and improves the [EEG Conformer](https://github.com/eeyhsong/EEG-Conformer) and [RGN](https://github.com/shiroger/Riemannian-Geometry-Networks), and we sincerely thank the creators of these open-source project.


### Repository Overview
This repository implements HSTRDA (Hybrid Sparse Transformer with Riemannian Geometry and Domain Adaptation), a deep learning framework for EEG motor imagery (MI) classification. The code is written in PyTorch and is evaluated on BCI Competition IV Dataset 2a,b under subject-dependent and domain-adaptation settings.

The implementation focuses on robust cross-subject generalization, addressing the key challenges of EEG decoding:

Non-stationarity across subjects

Low signal-to-noise ratio

Distribution shift between training and test subjects

Rather than relying on a single paradigm (CNNs or Transformers alone), this code integrates signal-aware geometry, efficient temporal modeling, and adversarial domain alignment.

### Abstract:


### Overall Framework:
![architecture of HSTRDA](main/architecture.png)

### Requirements:
Python 3.10

Pytorch 1.13.1


### Citation
Hope this code can be useful. I would appreciate you citing us in your paper. 😊


