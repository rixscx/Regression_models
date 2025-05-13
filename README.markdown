# Regression models 

## Overview
This Jupyter Notebook (`Types_of_Regression.ipynb`) demonstrates the implementation of a Multi-Layer Perceptron (MLP) regression model using Scikit-learn's `MLPRegressor`. It generates a synthetic dataset based on a sine function with added noise, trains an MLP model, and visualizes the actual data alongside the model's predictions.

## Contents
- **MLP Regression Example**:
  - Generates synthetic data using a sine function with Gaussian noise.
  - Implements an MLP regression model with two hidden layers (50 neurons each).
  - Trains the model using the Adam optimizer and ReLU activation function.
  - Visualizes the actual data points and the MLP predictions using Matplotlib.

## Prerequisites
To run the notebook, ensure you have the following Python libraries installed:
- `numpy`
- `matplotlib`
- `scikit-learn`

You can install them using pip:
```bash
pip install numpy matplotlib scikit-learn
```

## Usage
1. **Open the Notebook**:
   - Use Jupyter Notebook or JupyterLab to open `Types_of_Regression.ipynb`.
   - Alternatively, use an environment like Google Colab.

2. **Run the Cells**:
   - Execute the cells sequentially to generate the dataset, train the MLP model, and display the plot.
   - The final output is a scatter plot of the actual data and a line plot of the MLP predictions.

3. **Expected Output**:
   - A plot showing the actual data points (blue dots) and the MLP regression predictions (red line).

## Notes
- The random seed (`random_state=1`) ensures reproducibility of the results.
- The model is configured with 2000 iterations for training, which can be adjusted via the `max_iter` parameter.
- The notebook is designed for educational purposes to illustrate MLP regression.

## License
This project is unlicensed and intended for educational use.
