# Deep Learning Keras MNIST Image Classification

This repository contains a deep learning project leveraging Keras to classify noisy MNIST handwritten digit images. The project explores various neural network architectures, including dense neural networks, convolutional neural networks (CNNs), and ResNet models. It also includes implementations for cross-validation and performance evaluation.

## Getting Started
- 💡[Context](https://github.com/gaelleloutfi/deep-learning-keras-mnist-image-classification/blob/main/README.md#context)
- ⚙️[Setup Environment](https://github.com/gaelleloutfi/deep-learning-keras-mnist-image-classification/blob/main/README.md#setup-environment)
- 📂[Repository Structure](https://github.com/gaelleloutfi/deep-learning-keras-mnist-image-classification/blob/main/README.md#repository-structure)
- 🚀[Running the Project](https://github.com/gaelleloutfi/deep-learning-keras-mnist-image-classification/blob/main/README.md#running-the-project)
- 💌[Contacts](https://github.com/gaelleloutfi/deep-learning-keras-mnist-image-classification/blob/main/README.md#contacts)
- 
## Context
- Classification of MNIST handwritten digit images, including handling noisy data
- Implementation of different deep learning architectures:
  - Dense Neural Networks
  - Convolutional Neural Networks (CNNs)
  - ResNet architectures
- Cross-validation methods for robust performance assessment
- Comprehensive evaluation metrics

## Setup Environment
We use [pixi](https://github.com/prefix-dev/pixi) to manage dependencies and the project software environment.  
On Linux (or WSL for Windows) or macOS, Pixi can be installed by running the following command:
```bash
curl -fsSL https://pixi.sh/install.sh | sh
```
The executable `pixi` will hence be installed in the directory `~/.pixi/bin/`.  
In order to be able to use pixi, you need to add this directory to the `PATH` environment variable by running the following command:
```bash
echo 'export PATH=$PATH:$HOME/.pixi/bin' >> ~/.bashrc
```
Finally, you can enable command auto-completion with:
```bash
echo 'eval "$(pixi completion --shell bash)"' >> ~/.bashrc
source ~/.bashrc
```
To verify that Pixi is installed correctly, run the following command:
```bash
pixi --version
```
Clone the Github repository 
```bash
git clone https://github.com/gaelleloutfi/deep-learning-keras-mnist-image-classification.git
```

## Repository Structure
Below is a description of each file in the repository:
```
.
├── GaelleLoutfi_MNIST.ipynb          # Main Jupyter Notebook for training and evaluating the MNIST models  
├── MNIST_dataset_example.png         # Sample visualization of MNIST digits  
├── UniversiteParisCite_logo_horizontal_couleur_RVB.png  # University logo (used for presentation/reporting)  
│
├── train_images.npy                  # Training images (NumPy array)  
├── train_labels.npy                  # Training labels corresponding to training images   
├── test_images.npy                   # Test images (NumPy array)  
└── test_labels.npy                   # Test labels corresponding to test images  
├── README.md                         # Project overview and instructions  
```
## Running the Project
Start Jupyter Notebook:
```bash
pixi run jupyter notebook
```
Open our Notebook:
- Navigate to the project folder in the browser (Jupyter will open automatically)
- Open `GaelleLoutfi_MNIST.ipynb`
- 
## Contacts
- Academic Email: gaelle.loutfi@etu.u-paris.fr
- Personal Emails: gaelle.loutfi@gmail.com / gaelle.loutfi@lau.edu
**Repository:** [gaelleloutfi/deep-learning-keras-mnist-image-classification](https://github.com/gaelleloutfi/deep-learning-keras-mnist-image-classification)
