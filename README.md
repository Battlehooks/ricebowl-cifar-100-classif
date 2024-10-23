
# ResNet18 Variant Notebook

This repository contains a Jupyter Notebook that demonstrates a variant of the ResNet18 architecture for deep learning tasks using PyTorch. The setup instructions and usage details are outlined below.

## Setup Instructions

To run this notebook, please follow the steps below:

### 1. Install Python and Jupyter
Ensure that Python 3.10.x is installed on your machine along with Jupyter Lab. You can install them using the following commands:

```bash
pip install jupyterlab
```

### 2. Clone or Download the Repository
Clone this repository to your local machine or download it as a ZIP file and extract it.

```bash
git clone https://github.com/Battlehooks/ricebowl-cifar-100-classif.git
```

### 3. Install Dependencies

Navigate to the directory where `requirements.txt` is located and install all the dependencies:

```bash
pip install -r requirements.txt
```

The required libraries are listed in the `requirements.txt` file and include essential packages such as:

- Jupyter Lab and related extensions
- PyTorch, TorchVision, and Torchaudio
- NVIDIA CUDA libraries (for GPU acceleration)
- NumPy, tqdm for progress tracking
- Networkx for graph-based computations

### 4. Launch Jupyter Lab

To start working with the notebook, launch Jupyter Lab by running:

```bash
jupyter lab
```

Open the `ResNet18_Variant.ipynb` file from Jupyter Lab to start using the notebook.

## Notebook Overview

### `ResNet18_Variant.ipynb`
This notebook demonstrates the implementation of a custom ResNet18 variant using PyTorch. It covers the following:

- Building and training the ResNet18 model variant.
- Performing data loading and preprocessing.
- Training with support for GPU acceleration (CUDA).
- Evaluating model performance using various metrics.

You can modify the variable above such as `SEED`, `BEST_MODEL_PTH`, and `MODeL_PTH` to change it as you want

## GPU Support
This notebook is configured to leverage GPU support using CUDA for faster training and inference. Ensure you have the necessary NVIDIA drivers installed for GPU acceleration.

## Notes
- Make sure your GPU and CUDA versions are compatible with the PyTorch version specified in `requirements.txt`.
- For troubleshooting, refer to the official PyTorch documentation or contact the RiceBowl team.
