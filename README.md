# Alphabet-Inc. Stock-Forecasting
## Project Description
In this project I pulled data from Yahoo Finance on the historical data of Alpahbet Inc.'s stock value starting from 2004 upto 31/03/2023.
The collected data is then used for to build a model for time-series forecasting.
## Data Collection
In the data collection notebook I go over the process of pulling the data, selecting relevant features for the training of the Time-Series model, and final export
the data to a PostgreSQL database where it would be used to create visualizations in Power BI.
## Building The Model
The build_model notebook goes over the process of scaling the data, creating our model using Tensorflow and Keras, training the model, then evaluating
using the test set.
## Data Visualization
The model predictions for the last 687 days is then placed into PostgreSQL and passed to Power BI to create a visualization containing the
predicted closing share values over time, the actual closing share values over time, and a superimposed graph of the two meant to demonstrate
the degree of precision of the time-series model.
## Folder
The Power BI visualiation is provided in the visualizations folder, the data is provided in the data folder, and the saved model is provided
in the models folder.
