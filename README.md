# Neural Network Classification Projects

Welcome to the **Neural Network Classification Projects** repository! This collection includes three different neural network implementations showcasing various classification techniques, ranging from linear models to complex multi-class classifiers.

## Projects Overview

### 1. [Linear Neural Network Classification](./Linear_NN_Classification)
A simple linear neural network designed to classify binary data points. This project demonstrates:
- The fundamental principles of neural networks.
- Binary classification using Sigmoid activation.
- Visualizations of decision boundaries.

### 2. [Non-Linear Neural Network Classification](./NonLinear_NN_Classification)
A non-linear neural network leveraging ReLU activation in hidden layers for better performance on non-linearly separable datasets. Features include:
- Multi-layer perceptron with ReLU activation.
- Binary classification with decision boundary visualizations.

### 3. [Blobs Dataset Classification](./Blobs_Dataset)
A multi-class classification problem solved using a neural network. Highlights include:
- A synthetic dataset with four classes (`make_blobs`).
- Use of softmax activation for multi-class predictions.
- Visualizations of decision boundaries for training and testing datasets.

## Repository Structure
```
Neural_Network_Classification/
├── Linear_NN_Classification/
│   ├── linear_neural_network_classification.py
│   ├── input_linear_classification.png
│   ├── output_linear_classification.png
│   ├── README.md
├── NonLinear_NN_Classification/
│   ├── non_linear_neural_network_classification.py
│   ├── input_non_linear_classification.png
│   ├── output_non_linear_classification.png
│   ├── README.md
├── Blobs_Dataset/
│   ├── blobs_dataset_classification.py
│   ├── input_blobs_dataset.png
│   ├── output_blobs_dataset.png
│   ├── README.md
├── README.md  # This file
```

## Requirements
To run the projects, ensure you have the following installed:
- Python 3.x
- PyTorch
- Scikit-learn
- Matplotlib

Install dependencies using:
```bash
pip install torch scikit-learn matplotlib
```

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Neural_Network_Classification.git
   cd Neural_Network_Classification
   ```
2. Navigate to the project folder of your choice (e.g., `Linear_NN_Classification`) and run the respective script.


## Acknowledgments
- These projects were built using PyTorch and synthetic datasets generated with `sklearn`.

Feel free to explore the code and modify it to suit your needs. Contributions and feedback are welcome!

## License
This repository is licensed under the [MIT License](./LICENSE).

