# IGNORE FOR NOW
# Deep Learning Keras MNIST Image Classification

This repository contains a deep learning project leveraging Keras to classify noisy MNIST handwritten digit images. The project explores various neural network architectures, including dense neural networks, convolutional neural networks (CNNs), and ResNet models. It also includes implementations for cross-validation and performance evaluation.

## Features

- Classification of MNIST handwritten digit images, including handling noisy data
- Implementation of different deep learning architectures:
  - Dense Neural Networks
  - Convolutional Neural Networks (CNNs)
  - ResNet architectures
- Cross-validation methods for robust performance assessment
- Comprehensive evaluation metrics

## Repository Structure

Below is a description of each file in the repository:

- `model_dense.py` — Implements a dense (fully-connected) neural network for MNIST classification.
- `model_cnn.py` — Contains the architecture and training code for a convolutional neural network.
- `model_resnet.py` — Defines a ResNet-style architecture adapted for the MNIST dataset.
- `train.py` — Entry point for training models; handles data loading, model selection, and training loop.
- `evaluate.py` — Evaluates trained models on validation and test datasets, computes metrics.
- `cross_validation.py` — Scripts for k-fold cross-validation experiments.
- `utils.py` — Utility functions for preprocessing, data augmentation, and visualization.
- `requirements.txt` — Lists Python dependencies required to run the project.
- `README.md` — Project overview and instructions.
- `notebook_experiments.ipynb` — Interactive experiments and visualizations with model training results.

## Getting Started

### Prerequisites

- Python 3.x
- See `requirements.txt` for required Python packages.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gaelleloutfi/deep-learning-keras-mnist-image-classification.git
   cd deep-learning-keras-mnist-image-classification
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Project

To train a model:
```bash
python train.py --model cnn
```

**Repository:** [gaelleloutfi/deep-learning-keras-mnist-image-classification](https://github.com/gaelleloutfi/deep-learning-keras-mnist-image-classification)
