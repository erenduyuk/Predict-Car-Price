# Used Car Price Prediction

This Python script demonstrates how to build a machine learning model for predicting used car prices. It utilizes the TensorFlow library for creating a neural network and scikit-learn for data preprocessing and evaluation.

## Getting Started

These instructions will help you run the code on your local machine for development and testing purposes.

### Prerequisites

Before running the code, make sure you have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- TensorFlow


## Dataset

The dataset used for this project is stored in the `merc kopyası.xlsx` file. It contains information about various car features, including year, mileage, fuel type, and more.

## Data Preprocessing

- Data statistics are displayed to understand the dataset.
- The distribution of the car prices is visualized using a histogram.
- Correlation between numerical features and car prices is calculated.
- Outliers in the price column are removed.
- The dataset is filtered to exclude cars from the year 1970.

## Model

A neural network model is created with the following architecture:

- Input Layer (12 units, ReLU activation)
- Hidden Layers (12 units each, ReLU activation)
- Output Layer (1 unit)

The model is compiled using mean squared error (MSE) as the loss function and the Adam optimizer. It is trained on the data for 300 epochs.

## Model Evaluation

- Training and validation loss over epochs are plotted.
- Predictions are made on the test data, and mean absolute error (MAE) is calculated to evaluate the model's performance.

## Results

- The script displays the mean absolute error (MAE) between the predicted and actual car prices.
- A scatter plot is created to visualize the relationship between predicted and actual prices.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

