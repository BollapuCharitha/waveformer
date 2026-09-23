# Waveformer: Enhanced Android Malware Detection with Wavelet Transform and Transformer Fusion

## Overview

Waveformer is an Android malware detection project that uses machine learning and deep learning techniques to classify Android applications as **benign or malicious**.

The project focuses on extracting meaningful features from Android application permissions and transforming them into representations that can be processed by deep learning models.

## Objective

The main objective of Waveformer is to develop an effective approach for detecting Android malware by combining:

- Wavelet Transform for frequency-domain feature extraction
- Convolutional Neural Network (CNN) for feature learning
- Squeeze-and-Excitation (SE) attention for improving important feature representation
- Deep learning-based classification for benign and malware detection

## Project Workflow

```text
Android Application Permissions
            ↓
     Data Preprocessing
            ↓
     Feature Extraction
            ↓
      Wavelet Transform
            ↓
   Grayscale Image Representation
            ↓
       CNN + SE Attention
            ↓
       Feature Learning
            ↓
     Malware Classification
            ↓
   Benign / Malicious + Confidence
