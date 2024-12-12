# **Heartbeat Sound Classification Using DenseNet**

This project focuses on classifying heartbeat sounds using a DenseNet-based convolutional neural network (CNN). The input data consists of heartbeat audio signals transformed into spectrograms for visual feature extraction.

---

## **Project Overview**

1. **Data Preprocessing**:
   - Audio signals are converted into **spectrograms** for visual representation.
   - Data normalization and splitting into training, validation, and test sets are performed.
   - Implemented in: **`data_preprocessing.ipynb`**

2. **Model and Training**:
   - A DenseNet-inspired CNN architecture is implemented for feature extraction and classification.
   - Training, validation, and evaluation are conducted.
   - Implemented in: **`model_training.ipynb`**

---

## **Project Structure**

── preproces_data.ipynb   # Notebook for preprocessing heartbeat audio data
── train_model.ipynb       # Notebook for model implementation and training
── dataset /                      # Directory to store spectrograms and datasets

## Requirements
Install the required Python libraries:
pip install torch torchvision torchaudio numpy matplotlib


## How to Run
Preprocess the Data:
Run preproces_data.ipynb to convert audio data into spectrograms and split the data.

## Train the Model:

Run train_model.ipynb to train the DenseNet model on the preprocessed spectrograms.

