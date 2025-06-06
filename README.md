
# ECG Signal Classification for Arrhythmia Detection

This project implements a deep learning pipeline for classifying arrhythmias from ECG signals using the MIT-BIH Arrhythmia Dataset. It combines CNN and RNN layers to model both spatial and temporal patterns in ECG waveforms.

## 💡 Project Objectives

- Handle noisy, real-world physiological data from PhysioNet
- Preprocess ECG signals with filtering and segmentation
- Classify different types of arrhythmias using deep learning
- Simulate early-stage diagnostic tools for clinical assistance

## 🧰 Technologies Used

- Python, PyTorch
- WFDB for PhysioNet ECG signal access
- CNN + RNN model architecture
- Scikit-learn for evaluation metrics

## 🗃 Dataset

MIT-BIH Arrhythmia Database from PhysioNet  
🔗 [https://physionet.org/content/mitdb/1.0.0/](https://physionet.org/content/mitdb/1.0.0/)

## ⚙️ Features

- Load and visualize ECG signal data
- Apply Butterworth filtering and normalization
- Slice signals into time windows for supervised training
- Build and train a CNN-RNN model to classify arrhythmias
- Evaluate performance using accuracy, confusion matrix, F1 score

## 🏁 Getting Started

```bash
# Install dependencies
pip install wfdb torch numpy scipy scikit-learn matplotlib
```

To run:
- `train.py` – for model training
- `evaluate.py` – for testing on unseen ECG records

## 📊 Results

Achieved high classification accuracy across multiple arrhythmia types. Model demonstrates robust performance on noisy medical signal data.

