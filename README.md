# Accurate Semantic Segmentation of Aerial Imagery Using Attention Res U-Net Architecture

## 📄 IEEE Publication

[![IEEE Paper](https://img.shields.io/badge/IEEE-Published%20Paper-blue?style=for-the-badge&logo=ieee)](https://ieeexplore.ieee.org/document/10497287)

[![Full Paper](https://img.shields.io/badge/PDF-Full%20Research%20Paper-red?style=for-the-badge&logo=adobeacrobatreader)](./ESCI_1188.pdf)

This repository contains the implementation and research work behind our IEEE-published paper:

**"Accurate Semantic Segmentation of Aerial Imagery Using Attention Res U-Net Architecture"**

The work was presented at the:

**6th IEEE International Conference on Emerging Smart Computing and Informatics (ESCI 2024)**

---

## Why We Built This

Satellite imagery contains a huge amount of information that can help with:

- Smart city planning
- Urban development
- Land-use monitoring
- Environmental analysis
- Infrastructure management

The challenge is that computers must identify every pixel in an image and determine whether it belongs to a building, road, vegetation, water body, or other object.

Traditional image classification models can tell what exists in an image.

Semantic segmentation goes one step further by determining exactly where every object exists.

Our goal was to improve segmentation accuracy while preserving fine object boundaries in complex aerial imagery.

---

## What We Did

We developed an enhanced semantic segmentation model based on:

- U-Net Architecture
- Residual Learning
- Attention Mechanisms

The model combines the strengths of residual connections and attention gates to improve feature extraction and focus on the most relevant regions of an image.

The implementation was built using:

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- CUDA GPU Training

---

## Dataset

We trained and evaluated the model using the Dubai Aerial Imagery Dataset.

Dataset Characteristics:

- 72 high-resolution satellite images
- 6 semantic classes
- Building
- Road
- Vegetation
- Water
- Land
- Unlabeled regions

---

## Results

Our proposed Attention Res U-Net achieved:

| Metric | Result |
|----------|----------|
| Accuracy | **86.42%** |
| Mean IoU (mIoU) | **63.85%** |
| Validation Loss | **0.4420** |

Compared to the baseline U-Net architecture, the model produced:

✅ Sharper object boundaries

✅ Better feature localization

✅ Improved segmentation consistency

✅ More stable convergence during training

---

## Repository Structure

### simple_multi_unet_model.py

Contains the implementation of the segmentation architecture used during experimentation and training.

### training_the_areal_images.py

Contains:

- Data preprocessing
- Image preparation
- Model training
- Evaluation
- Visualization generation

---

## Research Paper

The complete research paper is available in this repository.

📄 Full Paper: `ESCI_1188.pdf`

Official IEEE Publication:

https://ieeexplore.ieee.org/document/10497287

---

## Authors

Rishindra Mateti and Research Team

IEEE ESCI 2024
