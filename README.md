# Impact_of_Music_on_EEG_Signals_of_Young_Adults
# EEG-based Analysis of Musical Impact on Brain Activity using Deep Learning

This project investigates how different music genres affect brain activity using EEG signals and deep learning models. It leverages neural networks to classify EEG responses and uncover genre-specific brainwave patterns.

---

## 📌 Objective

- **Goal**: Predict the impact of different music genres on brain activity using EEG data.
- **Dataset**: [NMED-RP (Naturalistic Music EEG Dataset - Rhythm Pilot)](https://zenodo.org/record/10438326)
- **Subjects**: Healthy individuals exposed to varied musical genres.
  
---

## Project Pipeline

### ✅ 1. EEG Preprocessing (Done)
- Channel selection
- Outlier thresholding
- Bandpass filtering (1–45 Hz)
- ICA-based artifact removal using MNE

### 🔬 2. Deep Learning Modeling (In Progress)
- EEGNet (Compact CNN for EEG)
- 1D CNN
- LSTM / BiLSTM
- CNN on spectrograms
- Transformer-based models

### 📊 3. Evaluation 
- Accuracy, precision, recall, F1-score
- ROC-AUC, confusion matrix

---

