Speech Emotion Recognition
Project Overview
This project involves the development of a Speech Emotion Recognition system using Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks. The goal is to recognize and classify emotions in speech from a dataset of voice recordings. The emotions included in the dataset are anxiety, fear, sad, calm, and neutral.

Dataset
The dataset comprises 20 voice recordings categorized into the following emotions:

Anxiety
Fear
Sad
Calm
Neutral
Each audio file in the dataset is labeled according to the emotion it represents.

Project Structure
data/: Directory containing the voice dataset.
src/: Source code for data processing, feature extraction, model training, and evaluation.
data_loader.py: Script to load and preprocess audio data.
feature_extraction.py: Script to extract features (e.g., MFCC, Spectrogram) from audio data.
model.py: Script defining the CNN-LSTM model architecture.
train.py: Script for training the model.
evaluate.py: Script for evaluating model performance.
requirements.txt: List of required Python packages.
README.md: This file.
