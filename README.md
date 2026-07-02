# QAIFE-Medical-Image-Classification
Source code for QAIFE, QFE, and CNN experiments on five MedMNIST datasets.

# QAIFE for Medical Image Classification

This repository contains the implementation of Quantum Attention Inspired Feature Extraction (QAIFE), Quantum Feature Extraction (QFE), and a matched lightweight CNN baseline for medical image classification using five MedMNIST datasets:

- BreastMNIST
- PneumoniaMNIST
- OrganCMNIST
- BloodMNIST
- RetinaMNIST

## Repository Structure

- `QAIFE/`: QAIFE master code implementations for each dataset.
- `QFE/`: QFE master code as baseline implementations for each dataset.
- `CNN/`: Matched lightweight CNN master code as baseline implementations for each dataset.
- `requirements.txt`: Python package dependencies.

## Experimental Protocol

All methods were evaluated using the same dataset preprocessing, training protocol, and five independent runs. The reported results in the manuscript correspond to the mean performance across the five runs. By default, the master code will call the Blood-MNIST dataset, please replace it with the appropriate dataset call.

## Installation

```bash
pip install -r requirements.txt
