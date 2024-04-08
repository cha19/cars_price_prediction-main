# Car Price Prediction

## Introduction
Welcome to the Car Price Prediction project! This repository contains code for building a machine learning model to predict car prices based on various features. We use a dataset available on Kaggle, apply a Linear Regression algorithm, and save our model using Pickle for future predictions.

## Dataset
The dataset used for this project is available on Kaggle. It includes various features that could potentially affect the price of a car, such as make, model, year, engine size, and more. You can download the dataset directly from Kaggle.

## Prerequisites
Before running this project, you will need the following:
- Python 3.x
- pip (Python package installer)

## Installation
To run this project, you need to install the required Python packages. You can install them using the following command:

```bash
pip install -r requirements.txt
```

This command will install all the necessary packages, including `scikit-learn`, `pandas`, `numpy`, and `pickle`, which are listed in the `requirements.txt` file.

## Usage
To predict car prices using the trained model:
1. Clone this repository to your local machine.
2. Download the dataset from Kaggle and place it in the `data/` directory.
3. Run the `application.py` script to train the model. This will save a `.pkl` file in the `models/` directory.

```bash
python application.py
```

4. Use `predict.py` to make predictions by passing the required features.

```bash
python predict.py --features [FEATURES]
```

Replace `[FEATURES]` with the actual car features you want to predict the price for.

## Training the Model
The `application.py` script handles the training of the Linear Regression model. It performs the following steps:
1. Loads the dataset.
2. Cleans and preprocesses the data.
3. Splits the data into training and test sets.
4. Trains the Linear Regression model.
5. Saves the trained model to disk using Pickle.

## Model
The trained model is a simple Linear Regression model which predicts the price of a car based on its features. The model is saved to disk as `LinearRegressionModel.pkl` inside the `models/` directory, allowing you to load the model without having to retrain it.

## License
This project is open-sourced under the [MIT License](LICENSE).

## Contributions
Contributions are welcome! Please feel free to submit a pull request.

## Contact
If you have any questions or feedback, please reach out to us at saicharan.gangili@gmail.com.