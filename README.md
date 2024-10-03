# EEG Signal Classification using CNN and LSTM

## Project Overview

This project focuses on classifying EEG signals using both **Convolutional Neural Networks (CNN)** and **Long Short-Term Memory Networks (LSTM)**. The goal is to detect specific events in EEG data based on spatial and temporal patterns. The project compares the performance of CNN and LSTM architectures on the same dataset, highlighting the strengths and weaknesses of each approach for EEG signal classification.

### Dataset
The dataset used consists of EEG signals with labels representing six different events:

1. HandStart
2. FirstDigitTouch
3. BothStartLoadPhase
4. LiftOff
5. Replace
6. BothReleased

Both CNN and LSTM models were trained and tested on this dataset to compare their performance in classifying the events.

Results and Comparison
The performance of the models on the EEG classification task is summarized below:

CNN Accuracy: 64-67%
LSTM Accuracy: 50-54%
Conclusion: CNN outperforms LSTM for this EEG classification task, likely due to the spatial nature of the data.

---

## Project Structure

```bash
├── data/                    # Directory for the dataset
├── models/                  # Saved model files (CNN and LSTM)
├── notebooks/               # Jupyter notebooks for exploratory data analysis and model training
├── src/                     # Python scripts for data preprocessing and training models
│   ├── cnn_model.py         # Script for CNN model
│   ├── lstm_model.py        # Script for LSTM model
│   └── hybrid_model.py      # Script for hybrid CNN-LSTM model
├── results/                 # Directory to store results (accuracy, loss curves)
├── README.md                # Project README file
└── requirements.txt         # Python dependencies


