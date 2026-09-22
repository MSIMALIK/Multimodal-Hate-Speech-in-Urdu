[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-brightgreen.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep_Learning-EE4C2C.svg)](https://pytorch.org/)
# Bridging Modalities and Languages: An Explainable Cross-lingual Multimodal Deep Learning Framework for Hate Speech Detection
The repository contains Jupyter notebooks for developing, training, and evaluating multimodal machine-learning/deep-learning pipelines that combine **text** and **image** information for hate vs. non-hate classification.

## 📊 Datasets Overview

The evaluation framework incorporates three benchmark datasets across Urdu, English, and Arabic to measure multimodal performance and cross-lingual generalization capabilities.

| Language | Modalities | Samples | Class Distribution (Hate / Non-Hate) | Kaggle Link |
| :--- | :--- | :--- | :--- | :--- |
| **Urdu** | Multimodal (Text + Image) | 11,000 | **Hate:** 5,500 <br> **Non-Hate:** 5,500 | [MMHS11K Urdu Dataset](https://www.kaggle.com/datasets/ahmedali001/mmhs11k-urdu-multimodal-hate-speech-dataset) |
| **English** | Multimodal (Text + Image) | 149,823 | **Hate:** 36,969 <br> **Non-Hate:** 112,854 | [Multimodal Hate Speech](https://www.kaggle.com/datasets/victorcallejasf/multimodal-hate-speech) |
| **Arabic** | Multimodal (Text + Image) | 3,061 | **Hate:** 398 <br> **Non-Hate:** 2,663 | [MAHED Arabic MMHS Dataset](https://www.kaggle.com/datasets/ahmedali001/mahed-arabic-multimodal-hate-speech-dataset) |

> **Note:** Dataset licenses and terms of use are controlled by their respective dataset owners. The repository license applies to the code in this repository, not automatically to third-party datasets.

## Repository Structure

```text
Multimodal-Hate-Speech-in-Urdu/
├── notebooks/          # Experiment, training, and evaluation notebooks
├── README.md           # Project documentation
├── requirements.txt    # Python dependencies
└── LICENSE             # Source-code license
```

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/MSIMALIK/Multimodal-Hate-Speech-in-Urdu.git
cd Multimodal-Hate-Speech-in-Urdu
```

### 2. Create a virtual environment

Using `venv`:

```bash
python -m venv .venv
```

Activate it on Linux/macOS:

```bash
source .venv/bin/activate
```

Activate it on Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Running the Notebooks

Start JupyterLab:

```bash
jupyter lab
```

Then open the notebooks in the `notebooks/` directory and update dataset paths where necessary.

## GPU Support

Deep-learning experiments will run substantially faster on a CUDA-compatible GPU. Install a PyTorch build appropriate for your CUDA version if GPU acceleration is required. Refer to the official PyTorch installation instructions for the correct build for your system.

## Responsible Use

This repository is intended for **research and educational use** in hate-speech detection and content moderation. The datasets may contain offensive, discriminatory, or otherwise harmful material. Users should handle such content carefully and follow the terms, licenses, and ethical requirements of the original datasets.

## License

The source code in this repository is released under the **MIT License**. See [`LICENSE`](LICENSE) for details.

Third-party datasets, pretrained models, and other external resources remain subject to their own licenses and terms of use.

## Citation

If you use this repository in academic work, please cite the repository and the original datasets or papers associated with the data and models you use.

Repository:

```text
MSIMALIK. Multimodal-Hate-Speech-in-Urdu.
https://github.com/MSIMALIK/Multimodal-Hate-Speech-in-Urdu
```
