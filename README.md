# Handwritten Digit Recognition with PyTorch

This project implements a **Handwritten Digit Recognition** model using **PyTorch** and the **MNIST dataset**. The model is trained to classify digits (0-9) based on handwritten input images.

## Installation & Requirements

Ensure you have Python installed, then install the necessary dependencies:

```sh
pip install torch torchvision matplotlib
```

## Usage

1. **Run the Jupyter Notebook:**
   ```sh
   jupyter notebook main.ipynb
   ```
2. The notebook loads the MNIST dataset and trains a neural network model to recognize digits.
3. The trained model is evaluated on test data, and sample predictions are visualized.

## Dataset

The project uses the **MNIST dataset**, a collection of 28x28 grayscale images of handwritten digits, commonly used for machine learning benchmarking. The dataset is automatically downloaded using `torchvision.datasets.MNIST`.

## Goals

1. Allow user to input its own image. 


## Acknowledgments

This implementation follows the tutorial from **NeuralNine**:
[NeuralNine - PyTorch Project: Handwritten Digit Recognition](https://www.youtube.com/watch?v=vBlO87ZAiiw).

