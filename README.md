### University Dissertation - 'Evaluating the use of different data as input for neural networks in the prediction of Ethereum cryptocurrency prices'

The purpose of this project is to combine machine learning techniques with a variety of indicators used by traders to predict cryptocurrency prices. This project focuses on the prediction for Ethereum (ETH) cryptocurrency.

<details><summary>SCHEDULE (Gantt Chart)</summary>
<p>

<img src="https://github.com/ZaraBhatti/Dissertation/blob/main/gantt.jpg" width=75% height=75%>
  
</p>
</details> 

<details><summary>PLAN</summary>
<p>

Both regression and classification algorithms are to be explored. 

#### Regression
To predict the future price of ETH, three Long Short-Term Memory (LSTM) neural network architectures will be created: 

- Many-to-Many Multi-Step LSTM (MM-LSTM)
- Encoder-Decoder LSTM (ED-LSTM)
- Bidirectional LSTM (BiLSTM)

#### Classification
The purpose of the classification task is to compare the best performing regression model with the same LSTM architecture but applied to classification instead. This model will aim to predict if the price will move up or down. Therefore the neural network architecture to be used will be determined after completion of the regression task. 

#### Metrics & Statistical Analysis

**Regression:**
The Root Mean Squared Error (RMSE) metric will be used to evaluate the regression models. The Mann-Whitney U Test will then be used to statistically compare metrics between the baseline models (using standard ETH prices as input) and each of the experimental models (utilising different technical indicators as input) of the same architecture.

**Classification:**
Accuracy and F1-score will evaluate the classification models. The Mann-Whitney U Test will again be used for statistical analysis of the models.

  
</p>
</details>

<details><summary>INDICATORS</summary>
<p>

There are 10 indicators that will be used as input:

| Indicator Type  | Name |
| :---: | :---: |
| Cryptocurrency  | Bitcoin (BTC)  |
| Cryptocurrecy  | Litecoin (LTC)  |
| Volatility | Bollinger Bands  |
| Volatility | Keltner Channels  |
| Trend  | Moving Average Convergence Divergence (MACD)   |
| Trend | Ichimoku Cloud  |
| Volume  | On-Balance Volume  |
| Volume  | Money Flow Index  |
| Momentum  | Relative Strength Indicator (RSI)  |
| Momentum  | Williams %R  |

  
</p>
</details>
 
<details><summary>RESULTS</summary>
<p>

None of the experimental regression models performed statistically significantly better than the baseline models. However, some indicators such as Keltner Channels and LTC price data caused the regression models to have statistically significantly poorer performances. 

A BiLSTM architecture was used for classification as this model gave the best baseline performance. The indicators that were used for the experimental classification models were BTC data, LTC data and Keltner Channels. The results were unclear as the metrics were contradictory and the predictions were imbalanced - this might have been due to there being a slight class imbalance in the test dataset. Due to this class imbalance, it is thought that more trust should be placed on F1-score, in which case, all three experimental models gave a statistically significantly poorer performance than baseline. This means that applying the BiLSTM architecture to the classification of ETH prices did not provide an improvement over regression. 

</p>
</details>  
