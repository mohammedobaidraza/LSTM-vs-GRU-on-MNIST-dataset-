# LSTM vs GRU Comparison on MNIST Dataset

This project compares the performance of Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) models on the MNIST dataset. The goal is to evaluate the training time and accuracy of both models.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

The project involves training and evaluating two types of recurrent neural networks (RNNs) — LSTM and GRU — on the MNIST dataset. The MNIST dataset consists of 28x28 grayscale images of handwritten digits (0-9). The models are trained to classify these digits.

### Models
- **LSTM**: A type of RNN that uses memory cells to maintain information over long periods.
- **GRU**: A simplified version of LSTM that uses fewer parameters and is computationally more efficient.

## Installation

To run this project, you need to have Python 3 installed along with the following libraries:

```bash
pip install torch torchvision numpy

```

## Usage
### Clone the repository: 
```bash
git clone https://github.com/obaidraza/lstm-vs-gru.git
cd lstm-vs-gru
```
Run the Jupyter Notebook:
```bash
jupyter notebook Assignment7(LSTM_vs_GRU).ipynb
```

## Results
After training both models for 5 epochs, the following results were obtained:

LSTM:

Training Time: 152.50 seconds

Test Accuracy: 78.54%

GRU:

Training Time: 182.14 seconds

Test Accuracy: 13.71%

Observations
The LSTM model achieved a significantly higher accuracy compared to the GRU model.

The GRU model took longer to train but did not perform well in terms of accuracy, which might indicate a need for hyperparameter tuning or further investigation.

## Conclusion
This project demonstrates the implementation and comparison of LSTM and GRU models on the MNIST dataset. While LSTM outperformed GRU in this specific scenario, further experimentation with different hyperparameters and architectures could yield better results for the GRU model.
