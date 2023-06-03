# Backpropagation

This repository contains a Jupyter Notebook that demonstrates the use of backpropagation to train a multi-layer perceptron (MLP) with a single hidden layer. The notebook explores different patterns and examines how quickly or slowly the weights converge. It also investigates the impact and interplay of various parameters such as learning rate, number of iterations, and number of data points.

## Notebook Author

Cesar Borroto

## Description

The notebook begins by generating two x-values and a corresponding y-value based on different patterns. It also includes a "bias" term, represented by a vector of 1s. You can choose one pattern by commenting out the others.

The notebook then defines helper functions, including a sigmoid function and a loss function based on logarithmic loss. It also includes a forward pass function, which performs a forward computation of the neural network using the input data (`x_mat`) and produces the output predictions (`y_pred`) along with the gradient of the log loss function.

The notebook further provides a function to plot the log loss and accuracy over iterations for visualization purposes.

The network parameters are initialized, and the training loop begins. In each iteration, the notebook performs a forward computation to obtain predictions and gradients. The weight matrices are then updated using gradient descent. The loss and accuracy are computed and stored for analysis. The notebook also prints the loss and accuracy for every 200th iteration.

Finally, the notebook visualizes the predicted answers, highlighting the correct and incorrect predictions.

## Dependencies

The notebook requires the following dependencies:
- `numpy`
- `matplotlib`

Make sure to install these dependencies before running the notebook.

## Usage

To run the notebook, follow these steps:
1. Install the required dependencies (`numpy` and `matplotlib`).
2. Launch Jupyter Notebook.
3. Open the `Backpropagation.ipynb` file.
4. Execute each cell in the notebook sequentially.

## Results

The notebook provides insights into the convergence of weights and the impact of different parameters on the training process. It visualizes the predicted answers and highlights the correct and incorrect predictions.
