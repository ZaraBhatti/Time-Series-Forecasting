4 models for **each** architecture were created with different input sequence lengths: 60-days, 30-days, 14-days and 7-days. All models provide a 7-day output.

Each model was tuned using the Random Search algorithm from Keras Tuner. 

The parameter settings from the model with the best performance, for each architecture, will be used as the parameters for the baseline and experimental models in the rest of the project.
