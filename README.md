# Nike Stock Prediction with LSTM and PySpark

This repository hosts a Big Data project aimed at predicting the stock prices of Nike using a custom-built Long Short-Term Memory (LSTM) model on PySpark. The project incorporates the MapReduce programming model to optimize gradient calculations, enhancing the efficiency of the model across distributed systems.

## Project Overview

The goal of this project is to develop a robust stock price predictor using advanced machine learning techniques. By building the LSTM model from scratch in PySpark, we leverage the power of distributed computing to handle large datasets more effectively. MapReduce is used to streamline the process of gradient descent, a critical aspect of training deep learning models.

### Key Features

- **Custom LSTM Model**: Tailored from the ground up to fit the specific nuances of stock price data.
- **PySpark Framework**: Utilizes Apache Spark’s powerful data processing capabilities to manage and analyze large datasets.
- **Gradient Calculation Optimization**: Implements MapReduce to distribute the gradient calculation workload, ensuring quick and efficient model training.
- **Data Visualization**: Includes plots and charts to visualize predictions and compare them against actual historical data.

## Dataset

The dataset comprises historical stock prices of Nike, which are used to train and validate the LSTM model. It includes open, high, low, close prices, and volume of stocks traded, providing a comprehensive set of features for analysis.

## Usage

To run this project, clone the repository and follow the steps below:

1. Set up a PySpark environment.
2. Load the Nike Stock dataset.
3. Run the Jupyter Notebook included in the repository to build and train the LSTM model.
4. Evaluate the model using the provided metrics and visualize the results.

## Requirements

- Python 3.6 or higher
- PySpark 3.0 or higher
- Matplotlib for data visualization
- Other common Python libraries (numpy, pandas)

## Contributing

Contributions to this project are welcome! Whether it's improving the model, enhancing the data visualization, or optimizing the MapReduce implementation, feel free to fork this repo and submit a pull request.
