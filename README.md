# Gold Prediction Project

This project is about predicting gold prices using a LSTM model. The model is trained on historical gold price data. The model used in this project is defined in the [gold.ipynb] file.

## Data

The model is trained on historical gold price data, which is stored in the `gold.csv` (https://www.kaggle.com/datasets/odins0n/monthly-gold-prices) file.

## Output

The output of the project is a prediction of future gold prices. The predicted gold prices are saved as `gold_price.h5`.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

- Python 3
- Jupyter Notebook

### Installing

A step by step series of examples that tell you how to get a development environment running:

1. Clone the repository to your local machine.
2. Install the necessary Python libraries. You can do this by running the following command:

```sh
pip install keras pandas sklearn numpy matplotlib