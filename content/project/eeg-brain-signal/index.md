---
title: EEG Signal Processing with DGCNN & ONNX
date: 2025-02-01
external_link: https://colab.research.google.com/drive/1QYzbt_zX_pZO2LWkt_aumfYf9Maqb8Rn?usp=sharing
tags:
  - EEG
  - Deep Learning
  - PyTorch
  - TorchEEG
  - ONNX
  - Signal Processing
---

A deep learning-based EEG signal processing project that classifies emotional states using the DREAMER dataset. The model is built using the DGCNN architecture from TorchEEG and optimized for fast inference via ONNX.

<!--more-->

**Key Features:**
- 🧠 Utilizes the **DREAMER dataset** for EEG-based emotion classification
- 🧩 Employs **DGCNN (Deep Graph Convolutional Neural Network)** tailored for EEG signal learning
- 🧼 EEG signals transformed into a 9x9 electrode grid format using TorchEEG’s `ToGrid()` transform
- ⚙️ Processes **four frequency bands** (delta, theta, alpha, beta) across **81 electrodes**
- 🏷️ Supports **binary classification** (e.g., positive vs. negative emotion)
- 🚀 Model exported to **ONNX format** for lightweight and high-speed deployment
- 🔄 Data loading and preprocessing handled with **PyTorch DataLoader** and TorchEEG’s built-in utilities