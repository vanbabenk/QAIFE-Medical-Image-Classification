# QAIFE for Medical Image Classification
Source code for QAIFE, QFE, and CNN experiments on five MedMNIST datasets.

This repository contains the implementation of Quantum Attention Inspired Feature Extraction (QAIFE), Quantum Feature Extraction (QFE), and a matched lightweight CNN baseline for medical image classification using five MedMNIST datasets:

- BreastMNIST
- PneumoniaMNIST
- OrganCMNIST
- BloodMNIST
- RetinaMNIST

## Repository Structure

- `notebooks/3_QAIFE.ipynb`: QAIFE master code implementations for each dataset.
- `notebooks/2_QFE.ipynb`: QFE master code as baseline implementations for each dataset.
- `notebooks/1_CNN.ipynb`: Matched lightweight CNN master code as baseline implementations for each dataset.
- `requirements.txt`: Python package dependencies.

## Experimental Protocol

All methods were evaluated using the same dataset preprocessing, training protocol, and five independent runs. The reported results in the manuscript correspond to the mean performance across the five runs. By default, the master code will call the Blood-MNIST dataset, please replace it with the appropriate dataset call.

## Installation
pip install -r requirements.txt

## Usage Example
notebooks/3_QAIFE.ipynb

## Run the code in Google Colab
CNN Code:
[![Convolutional Neural Network](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vanbabenk/QAIFE-Medical-Image-Classification/blob/main/notebooks/1_CNN.ipynb)

QFE Code:
[![Quantum Feature Extraction](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vanbabenk/QAIFE-Medical-Image-Classification/blob/main/notebooks/2_QFE.ipynb)

QAIFE Code:
[![Quantum Attention Inspired Feature Extraction](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vanbabenk/QAIFE-Medical-Image-Classification/blob/main/notebooks/3_QAIFE.ipynb)

## CITATION
If you use this code, please cite:

Ifran Lindu Mahargya et al., "Novel Quantum Attention Inspired Feature Extraction for Efficient Medical Classification", submitted to MULTIMEDIA TOOLS AND APPLICATIONS - SPRINGER.
