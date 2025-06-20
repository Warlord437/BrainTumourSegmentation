# 🧠 Brain Tumor Segmentation with U-Net

This repository contains a full implementation of a **brain tumor segmentation pipeline using U-Net**. The project demonstrates how to segment tumor regions from brain MRI scans using deep learning.

![UNet Architecture](https://i.imgur.com/lKZGO0C.png)

---

## 📌 Project Overview

This project includes:
- Preprocessing and diagnosis label creation
- Visualization of MRI scans and masks
- Splitting data into train/val/test
- Custom data generators with augmentation
- U-Net model architecture
- Custom loss functions (Dice, BCE, IoU)
- Training with callbacks (EarlyStopping, ReduceLRO)
- Evaluation and visualization of predictions

---

## 📁 Dataset

- **Source**: [Kaggle LGG MRI Segmentation](https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation)
- **Description**: T1-weighted MRI scans with corresponding tumor masks

Please place the dataset under:
