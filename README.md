# Dysarthria Classification Using CNNs on Audio Data

This repository contains the code for classifying dysarthria using Convolutional Neural Networks (CNNs) on audio recordings. Dysarthria is a motor speech disorder that results in unclear speech. This project aims to develop a model that can accurately classify dysarthric and non-dysarthric speech samples.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

Dysarthria is caused by muscle weakness affecting speech clarity. Traditional diagnostic methods rely on subjective assessments, which can be supplemented by automated classification using machine learning techniques. This project leverages CNNs to classify dysarthria from audio recordings, providing an objective and efficient diagnostic tool.

## Dataset

The dataset used in this project consists of audio recordings of speech samples from individuals with and without dysarthria. Each recording is labeled for binary classification. The dataset can be found on Kaggle: [Dysarthria Detection Dataset](https://www.kaggle.com/datasets/iamhungundji/dysarthria-detection).

## Model Architecture

The CNN model is designed with the following layers:

- **Input Layer:** Accepts the preprocessed audio features.
- **Convolutional Layers:** Extracts local patterns in the audio features.
- **Pooling Layers:** Reduces dimensionality and retains important features.
- **Fully Connected Layers:** Combines the features for final classification.
- **Output Layer:** Provides the probability of the input being dysarthric or non-dysarthric.

## Results

The trained CNN model achieves high accuracy in classifying dysarthric speech. Below are some key performance metrics:

|                | Precision | Recall | F1-Score | Support |
|----------------|-----------|--------|----------|---------|
| Non-Dysarthric (0.0) | 0.97      | 0.91   | 0.94     | 151     |
| Dysarthric (1.0)    | 0.92      | 0.97   | 0.94     | 149     |
| **Accuracy**        |           |        | 0.94     | 300     |
| **Macro Avg**       | 0.94      | 0.94   | 0.94     | 300     |
| **Weighted Avg**    | 0.94      | 0.94   | 0.94     | 300     |





