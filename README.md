# predict-bitcoin

## CryptoCurrency prediction using Deep Recurrent Neural Networks

This repository contains various Machine learning models used in industry to predict stock prices and cryptocurrency in finance industry.

- Fundamental analysis of the bitcoin price using Yahoo Finance
- Data Visualization using Seaborn
- Recurrent Neural Networks / Long Short Term Memory Networks
- Each model is compared against each other to highlight pros and cons of each model.

Install
This project requires Python and the following Python libraries installed:

- NumPy
- Pandas
- matplotlib
- fastai
- pytorch
You will also need to have software installed to run and execute a Jupyter Notebook.

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

## Code
The source code is divided into multiple sections following the machine learning design pattern of : Data Exploration, Training, Testing and Hyperparameter Optimization. You can view the precompiled version of the notebook or you can rerun the entire notebook. The datasets are made available on public S3 Buckets. Running the notebook, will automatically download the datasets for you.

## Run
In a terminal or command window,run one of the following commands:

jupyter notebook BitcoinPredictionRNN.ipynb

This will open the Jupyter Notebook software and project file in your browser.

## Data
BitCoin Price Data from Jan 2015- August 2018. The prices are as per coinbase cryptoexchange. There were many missing values and forward strategy was used to fill these missing values.

### Features BitCoin Price Data from August 2019 - July 2020
 
### Target Variable Close Price: Close price of Bitcoin for each day
