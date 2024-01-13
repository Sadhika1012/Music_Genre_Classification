# Music Genre Classifier 

## Overview

This repository contains the code for a music genre classifier built using various deep learning models.The implemented models include Artificial Neural Networks (ANN), Recurrent Neural Networks (RNN), Long Short-Term Memory networks (LSTM), and, finally, a Weighted k-Nearest Neighbors (kNN) approach.

## Dataset

The dataset used for training and evaluation is well-balanced with respect to different music genres. It encompasses up to 27 features providing a comprehensive representation of the audio characteristics of the songs.

## Implemented Models

### 1. Artificial Neural Network (ANN)

The project includes a simple ANN model, a class of deep learning models inspired by the structure and function of the human brain. The ANN is trained on the dataset to learn the patterns and relationships between the input features and music genres.

### 2. Recurrent Neural Network (RNN)

The implementation features RNN model, designed to capture sequential dependencies in the data. This is particularly useful for analyzing music, where the order of notes and beats plays a crucial role in determining the genre.

### 3. Long Short-Term Memory (LSTM)

A Long Short-Term Memory (LSTM) network is utilized to address the challenges of capturing long-term dependencies in sequential data. LSTMs are well-suited for tasks involving time series or sequential patterns, making them ideal for analyzing musical sequences.

### 4. Weighted k-Nearest Neighbors (kNN)

In addition to the deep learning models, a Weighted k-Nearest Neighbors (kNN) approach is implemented. This model leverages a non-parametric, instance-based learning method, where the classification is based on the majority class among the k-nearest neighbors in the feature space. The weights assigned to neighbors contribute to a more nuanced classification.

## Evaluation

The accuracy of each implemented model has been assessed on a validation set. kNN has given the highest accuracy so far, at 91%.

