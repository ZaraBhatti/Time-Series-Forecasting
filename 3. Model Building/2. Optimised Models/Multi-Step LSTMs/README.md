The 14-day input, 7-day output model gave the best performance as it gave the lowest RMSE score therefore the tuned parameters from this optimisation will be used for all of the MM-LSTM models in the rest of the project. The parameters and their optimal settings are listed below:

| Parameter  | Value |
| :---: | :---: |
| Input Sequence Length  | 14 days  |
| Output Sequence Length  | 7 days  |
| Number of Hidden Layers | 2 |
| Unit Size | 80 |
| Learning Rate | 0.001 |
| Dropout Size | 0.3 |
| Epochs | 61 |
