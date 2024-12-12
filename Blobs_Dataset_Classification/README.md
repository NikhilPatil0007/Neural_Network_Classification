
---

### 3. Blobs Dataset Classification (`blobs_dataset_classification.py`)

```markdown
# Blobs Dataset Classification

## Overview
This project demonstrates a multi-class classification problem using a neural network. The dataset is generated using `make_blobs` from `sklearn`. The model is designed with ReLU activation in hidden layers and softmax activation in the output layer for multi-class classification.

## Features
- Multi-layer perceptron with ReLU activation in hidden layers.
- Multi-class classification using softmax activation.
- Visualizes decision boundaries for training and testing datasets.

## Dataset
- **Source**: Synthetic dataset generated with `make_blobs`.
- **Description**: Two features and four classes.

## Model Architecture
- Input Layer: 2 neurons.
- Two Hidden Layers: 8 neurons each with ReLU activation.
- Output Layer: 4 neurons with softmax activation.

## Dependencies
- Python
- PyTorch
- Scikit-learn
- Matplotlib
