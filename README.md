# Concrete Strength Prediction

This project aims to predict the compressive strength of concrete using a regression model built with TensorFlow.

## Overview

The provided code performs the following tasks:

- Imports necessary libraries including pandas, numpy, TensorFlow, and scikit-learn.
- Reads a CSV file containing concrete data (parameters: Cement,Blast Furnace Slag,Fly Ash,Water,Superplasticizer,Coarse Aggregate,Fine Aggregate,Age,Strength) and preprocesses/cleans it.
- Defines a regression model using TensorFlow's Keras API.
- Splits the data into training and testing sets.
- Trains the regression model using the training data.
- Evaluates the model's performance on the testing data.
- Calculates the mean squared error (MSE) between the predicted concrete strength and the actual strength.

## Dependencies

- pandas
- numpy
- TensorFlow
- scikit-learn

## Usage

1. Install the required dependencies using `pip`:

    ```bash
    pip install pandas numpy tensorflow scikit-learn
    ```

2. Clone the repository:

    ```bash
    git clone https://github.com/your-username/concrete-strength-prediction.git
    ```

3. Navigate to the project directory:

    ```bash
    cd concrete-strength-prediction
    ```

4. Run the script:

    ```bash
    python concrete_strength_prediction.py
    ```

## Results

The script outputs the mean squared error (MSE) and the standard deviation of MSE calculated from multiple iterations of training and testing the model.
