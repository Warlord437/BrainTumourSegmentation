Brain Tumor Segmentation with U-Net
This project implements an end-to-end pipeline for brain tumor segmentation from MRI images using the U-Net deep learning architecture. It leverages TensorFlow and Keras to train, validate, and test a model that can automatically detect and segment tumor regions in brain MRIs.
<br>

📋 Table of Contents
Overview

Dataset

Project Structure

Installation & Setup

Usage

Results & Visualization

Model Architecture

Citations & References

🧠 Overview
Accurate and fast brain tumor segmentation is critical for effective diagnosis and treatment planning. This repository demonstrates a U-Net-based segmentation workflow, including:

Data preprocessing and visualization

Data augmentation

Model building (U-Net)

Custom loss functions (Dice, IoU, BCE-Dice)

Model training, validation, and testing

Visual inspection of predictions

📊 Dataset
Source: Kaggle LGG MRI Segmentation

Description: T1-weighted brain MRIs with corresponding manually-annotated tumor masks.

