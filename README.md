# Handwritten Digit Recognition with PyTorch

This project implements a Handwritten Digit Recognition system using PyTorch and the MNIST dataset. The system allows users to draw digits on a canvas and uses a trained neural network model to predict the drawn digit. The model is trained on the MNIST dataset, which consists of $28\times 28$ grayscale images of handwritten digits (0-9).

## Features

- Interactive Canvas: Draw digits using your mouse.
- Real-Time Prediction: Predict the drawn digit using a pre-trained PyTorch model.
- Clear Canvas: Reset the canvas to draw a new digit.
- Visualization: Display the processed image and prediction result.

## Installation & Requirements

Ensure you have Python installed, then install the necessary dependencies:

```sh
pip install torch torchvision matplotlib pillow
```

## Usage

1. Run the Jupyter Notebook:
   ```sh
   jupyter notebook main.ipynb
   ```
2. Draw a Digit: Use your mouse to draw a digit on the canvas.
3. Predict: Click the "Predict" button to see the model's prediction.
4. Clear: Click the "Clear" button to reset the canvas and draw a new digit.

## How It Works

1. Drawing: The user draws a digit on a Tkinter canvas.
2. Preprocessing: The drawn image is captured, resized to $28\times 28$ pixels, and preprocessed to match the MNIST dataset format (grayscale, normalized, and inverted).
3. Prediction: The preprocessed image is passed to a pre-trained PyTorch model, which predicts the digit.
4. Result: The predicted digit is displayed, and the processed image is shown using `matplotlib`.

## Code Structure

- Model: The neural network model is defined and trained using PyTorch.
- GUI: The graphical user interface is built using Tkinter.
- Preprocessing: The drawn image is preprocessed to match the MNIST dataset format.
- Prediction: The pre-trained model predicts the digit from the processed image.

## Resources

The following resources were used to understand and implement the handwritten digit recognition project:

1. [NeuralNine - PyTorch Project: Handwritten Digit Recognition](https://www.youtube.com/watch?v=vBlO87ZAiiw)
2. [GitHub - Pytorch Handwritten Digit Recognition](https://github.com/billy-enrizky/Pytorch-Handwritten-Digit-Recognition)
3. [Matplotlib Image Tutorial](https://matplotlib.org/stable/tutorials/images.html)
4. [Real Python - Tkinter GUI Tutorial](https://realpython.com/python-gui-tkinter/#building-your-first-python-gui-application-with-tkinter)
5. [Kaggle - Handwritten Digit Recognition with GUI](https://www.kaggle.com/code/ahmedelmaamounamin/handwritten-digit-recognition-with-gui/code#Handwritten-Digit-Recognition-with-GUI)

---
## License

This project is open-source and available under the MIT License. Feel free to use, modify, and distribute it as needed.

---