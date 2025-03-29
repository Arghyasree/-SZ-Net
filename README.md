# SZ-Net
A Hybrid CNN-BiLSTM-BiGRU Framework for Schizophrenia Detection and Classification using Electroencephalogram Signals

## 🧠 Overview
Schizophrenia (SZ) is a complex mental health condition characterized by delusions, disorganized thinking, hallucinations, and cognitive impairments. Its heterogeneous nature makes diagnosis particularly challenging. Electroencephalography (EEG), which records brain electrical activity through scalp electrodes, offers valuable insights into SZ detection due to its high temporal resolution.

In this project, we introduce SZ-Net, a hybrid deep learning framework that combines:

Convolutional Neural Networks (CNN) for spatial feature extraction.

Bidirectional Long Short-Term Memory (BiLSTM) and Bidirectional Gated Recurrent Units (BiGRU) for temporal pattern analysis.

Channel Attention mechanism to enhance model interpretability and accuracy.


<div align="center">
    <img src="https://github.com/user-attachments/assets/773d5855-516c-426b-8031-dec3e0befb87" alt="Overall pipeline of our proposed approach for EEG-based SZ diagnosis" width="800">
    <p>Overall pipeline of our proposed approach for EEG-based SZ diagnosis</p>
</div>



## 📊 Datasets
The model is evaluated on two benchmark EEG datasets:

[MSU Dataset](http://brain.bio.msu.ru/eeg_schizophrenia.htm): Collected from M.V. Lomonosov Moscow State University, comprising 39 healthy and 45 SZ patients.

[Kaggle EEG Dataset](https://www.kaggle.com/datasets/broach/button-tone-sz): Derived from a basic sensory task in SZ, comprising 32 healthy and 49 SZ patients.

## 🚀 Performance Highlights

MSU Dataset: Achieved 98.21% accuracy, surpassing existing state-of-the-art models.

Kaggle EEG Dataset: Achieved 99.27% accuracy, demonstrating the model's exceptional classification capability.

## 🤝 Acknowledgments

Supervisor: [Dr. Pawan Kumar Singh](https://scholar.google.co.in/citations?user=LctgJHoAAAAJ&hl=en)

