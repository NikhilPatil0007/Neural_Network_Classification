
---

### 2. Non-Linear Neural Network Classification 

```markdown
# Non-Linear Neural Network Classification

## Overview
This project uses a non-linear neural network to classify non-linearly separable data. The model incorporates ReLU activation functions in its hidden layers to improve performance on circular datasets.

## Features
- Multi-layer perceptron with ReLU activation in hidden layers.
- Binary classification using the Sigmoid activation function.
- Visualizes decision boundaries for training and testing datasets.

## Dataset
- **Source**: Synthetic dataset generated with `make_circles`.
- **Description**: Two features (`X1` and `X2`) with binary labels.

## Model Architecture
- Input Layer: 2 neurons.
- Two Hidden Layers: 10 neurons each with ReLU activation.
- Output Layer: 1 neuron with sigmoid activation.

## Dependencies
- Python
- PyTorch
- Scikit-learn
- Matplotlib

