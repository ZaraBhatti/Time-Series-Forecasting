All of the models were built using Keras and Tensorflow on Google Colaboratory.

The 'Standard_ETH_input_models_(BASELINE)' file contains all 3 model architectures using only the standard ETH data as input. The average RMSE scores for the 3 baseline models have been saved in three seperate .csv files so that they can be imported into other Jupyter Notebook files for statistical analysis purposes:

- baselineScores_a : Contains the RMSE scores for the Multi-Step LSTM model (named Model A in the code)
- baselineScores_b : Contains the RMSE scores for the ED-LSTM (named Model B in the code)
- baselineScores_c : Contains the RMSE scores for the BiLSTM (named Model C in the code)

The remaining 10 code files each contain the 3 types of models using a specific indicator as input. The files also contain the statistical comparison between the results of these models and the baseline scores saved in the .csv files.
