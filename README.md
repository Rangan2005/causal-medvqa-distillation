# Causal-medvqa-distillation


## Overview

This repository contains research on causal inference in Medical Visual Question Answering (MedVQA) with knowledge distillation techniques. The project explores how to enhance VQA models through causal reasoning and model distillation across multiple medical imaging datasets.

## 📚 Datasets & Notebooks

### 1. **Causal_Path_VQA.ipynb**
Investigation of causal pathways in visual question answering, analyzing how image regions contribute to answer generation.

### 2. **Causal_SLAKE.ipynb**
Causal analysis applied to the SLAKE dataset (Chinese medical VQA dataset). Explores causal relationships in multilingual medical QA scenarios.

### 3. **Causal_VQA_RAD.ipynb**
Causal inference experiments on the RAD (Radiology) dataset, focusing on radiology-specific visual question answering tasks.

## 🎯 Key Research Areas

- **Causal Inference**: Identifying true causal relationships vs. spurious correlations in visual reasoning
- **Medical VQA**: Domain-specific visual understanding for medical images
- **Knowledge Distillation**: Transferring knowledge from larger models to smaller, more efficient ones
- **Multi-dataset Analysis**: Evaluation across diverse medical VQA benchmarks (PathVQA, SLAKE, RAD)

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required libraries (see individual notebooks for imports):
  - PyTorch
  - torchvision
  - pandas, numpy
  - matplotlib, seaborn

### Usage

1. Clone the repository:
```bash
git clone https://github.com/Rangan2005/causal-medvqa-distillation.git
cd causal-medvqa-distillation
```

2. Open and run the notebooks in Jupyter:
```bash
jupyter notebook
```

3. Select the notebook corresponding to your dataset of interest:
* Causal_Path_VQA.ipynb - for PathVQA dataset experiments
* Causal_SLAKE.ipynb - for SLAKE dataset experiments
* Causal_VQA_RAD.ipynb - for RAD dataset experiments
