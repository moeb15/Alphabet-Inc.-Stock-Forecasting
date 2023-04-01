# Alphabet-Inc. Stock-Forecasting
In this project I pulled data from Yahoo Finance on the historical data of Alpahbet Inc.'s stock value starting from 2004 upto 31/03/2023. 
In the data collection notebook I go over the process of pulling the data, selecting relevant features for the training of the Time-Series model, and final export
the data to a PostgreSQL database where it would be used to create visualizations in Power BI.
The build_model notebook goes over the process of scaling the data, creating our model using Tensorflow and Keras, training the model, then evaluating
using the test set.
The Power BI visualiation is provided in the visualizations folder, the data is provided in the data folder, and the saved model is provided
in the models folder.
