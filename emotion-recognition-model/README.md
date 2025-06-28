# Emotion Recognition from Speech

This project aims to develop a deep learning model that can recognize human emotions based on speech audio inputs. It utilizes Mel Frequency Cepstral Coefficients (MFCCs) for feature extraction and a neural network for classification. The model is trained to classify speech samples into emotions such as angry, happy, sad, neutral, etc.

## Table of Contents

- Project Overview
- Dataset
- Features Used
- Model Architecture
- Installation & Setup
- How to Run
- Results
- Limitations
- Future Work
- License

## Project Overview

Understanding human emotions from speech has applications in virtual assistants, mental health monitoring, human-computer interaction, and customer service. This project processes raw audio data, extracts acoustic features using librosa, and trains a neural network using TensorFlow/Keras to classify emotions from speech.

## Dataset

- Dataset Used: RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
- Number of Emotion Classes: Calm, Happy, Sad, Angry, Fearful, Disgust, Surprised, Neutral
- Total Samples: ~196 per emotion
- Sampling Rate: 48 kHz (converted to 22.05 kHz for processing)

## Features Used

- MFCC (Mel Frequency Cepstral Coefficients)
- Zero Crossing Rate
- Chroma Frequencies
- Spectral Centroid
- Root Mean Square Energy

## Model Architecture

- Input Layer: MFCC feature vector (e.g., 40 coefficients)
- Hidden Layers: Dense layers with ReLU activation
- Dropout Layers for regularization
- Output Layer: Softmax activation for multi-class classification
- Loss Function: Categorical Crossentropy
- Optimizer: Adam
- Metrics: Accuracy
