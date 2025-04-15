# CapST: Capsule Networks with Spatio-Temporal Attention for Deepfake Model Attribution

This repository will provide the official code for our paper:

> **CapST: Leveraging Capsule Networks and Temporal Attention for Accurate Model Attribution in Deep-fake Videos**  
> *Wasim Ahmad, Yan-Tsung Peng, Yuan-Hao Chang, Gaddisa Olani Ganfure, Sarwar Khan*  
> *ACM Transactions on Multimedia Computing, Communications and Applications (TOMM)*  
> DOI: [10.1145/3715138](https://doi.org/10.1145/3715138)

---

## 📘 Abstract

Deep-fake videos created using face-swapping techniques pose serious security and misinformation risks. While most research focuses on distinguishing real from fake content, our work shifts the focus to **model attribution** — identifying *which* generative model was used to produce a given deep-fake.

We propose **CapST**, a novel Capsule-Spatial-Temporal architecture that:
- Extracts spatial features using a modified VGG19 (first 26 layers),
- Leverages **Capsule Networks** to capture hierarchical relationships among features, and
- Applies **temporal attention** to aggregate frame-wise evidence across videos.

CapST is evaluated on:
- **DFDM**: Deepfakes from Different Models (autoencoder-based)
- **GANGen-Detection**: GAN-generated Deepfake images (only fake samples used)

The model achieves high accuracy for model attribution while maintaining computational efficiency — making it practical for real-world forensic applications.

> 🔓 **Code and pretrained models will be released soon.**

---

## 🧠 Highlights

- 🧩 Combines Capsule Networks with temporal attention for deepfake video analysis
- 🧠 Strong spatial modeling of subtle generative artifacts
- 🎥 Frame-wise and video-level fusion for robust attribution
- 💡 Supports multiclass attribution instead of binary classification
- 🧪 Evaluated on DFDM and GANGen datasets

---

## 📦 Repository Contents (Planned)

- [ ] CapST model architecture (PyTorch)
- [ ] Capsule + temporal attention modules
- [ ] Training & evaluation scripts
- [ ] Dataset loading utilities for DFDM and GANGen
- [ ] Pretrained model checkpoints

---

## 🚀 Getting Started (Coming Soon)

> Instructions for environment setup, training, and inference will be provided when the code is released.

---

## 📄 Citation

If you use this work in your research, please cite:

```bibtex
@article{ahmad2025capst,
author = {Ahmad, Wasim and Peng, Yan-Tsung and Chang, Yuan-Hao and Ganfure, Gaddisa Olani and Khan, Sarwar},
title = {CapST: Leveraging Capsule Networks and Temporal Attention for Accurate Model Attribution in Deep-fake Videos},
year = {2025},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
issn = {1551-6857},
url = {https://doi.org/10.1145/3715138},
doi = {10.1145/3715138},
journal = {ACM Trans. Multimedia Comput. Commun. Appl.},
month = jan,
keywords = {Deepfake, Efficient Deep-fake Model Attribution (DFMA), Capsule Network, Dynamic Routing Algorithm (DRA), GAN’s, Spatial-Temporal Attention (STA), Video Forensics, Model Attribution, Temporal Analysis}
}
