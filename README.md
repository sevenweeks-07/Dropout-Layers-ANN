# Dropout Notebook

This notebook demonstrates the use of dropout in a neural network to prevent overfitting. The notebook is divided into several sections, including data generation, model creation, and evaluation.

## Sections

1. **Generate Data**
   - The data is generated using `np.linspace` and `np.array` to create training and testing datasets.

2. **Regression Model**
   - A simple regression model is created using TensorFlow and Keras. The model consists of two dense layers with ReLU activation and a linear output layer.
   - The model is trained on the generated data and evaluated using mean squared error (MSE).

3. **Dropout Model**
   - A similar regression model is created, but this time dropout layers are added after each dense layer to prevent overfitting.
   - The model is trained and evaluated in the same manner as the regression model.

4. **Visualization**
   - The results of both models are visualized using `matplotlib` to compare their performance on the test data.

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib
- Scikit-learn

## Usage

1. **Install Dependencies**
   ```bash
   pip install tensorflow numpy matplotlib scikit-learn