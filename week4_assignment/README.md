# 📘 Week 4 — AI Bootcamp Assignments

This repository contains all the work completed for **Week 4** of the AI Bootcamp. The focus is on building computer vision pipelines, training CNNs, applying transfer learning, and exporting models for deployment.

## 📂 Repository Structure
```
week4_assignment/
├── M1_assignment
├── M2_assignment
├── M4_assignment
└── weekly_project
```

## 🔹 Module 1 (M1) — Data Pipeline & Augmentation
**Goal:** Build robust preprocessing pipelines to improve model generalization.

**Covered topics:**
- Data augmentation (random crop, flip, rotation)
- Normalization using dataset or ImageNet statistics
- Creating PyTorch DataLoaders

**Outcome:** Reduced overfitting and improved validation performance.

## 🔹 Module 2 (M2) — Model Training & Evaluation
**Goal:** Train CNN models and evaluate their performance.

**Covered topics:**
- Training and validation loops
- Loss tracking and accuracy calculation
- Visualization of learning curves

**Outcome:** Reliable training workflow with performance monitoring.

## 🔹 Module 4 (M4) — Transfer Learning & Fine-Tuning
**Goal:** Adapt pre-trained models for new datasets.

**Covered topics:**
- Feature extraction vs fine-tuning
- Freezing/unfreezing model layers
- Modifying classifier heads
- Exporting models to ONNX

**Outcome:** Efficient model adaptation with improved accuracy.

## 🔹 Weekly Project — End-to-End Image Classification
**Goal:** Build a complete pipeline from data loading to deployment.

**Pipeline:**
1. Data preparation
2. Model training
3. Validation and visualization
4. ONNX export
5. ONNX Runtime inference

**Outcome:** Fully deployable image classification model.

## ⚙️ Requirements
- Python 3.10+
- torch, torchvision
- numpy, matplotlib
- onnx, onnxruntime

Install with:
```
pip install torch torchvision numpy matplotlib onnx onnxruntime
```

