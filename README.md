# Stock-Prediction-Project-May-2023-

**Overview**
This project aimed to analyze historical stock data obtained from Yahoo Finance and utilized LSTM, a subtype of the Recurrent Neural Network (RNN), for stock price prediction. Emphasis was placed on the stocks of Microsoft (MSFT) and Samsung (SMSNG) to discern their correlation coefficients.

**Data Exploration**
Source: Stock data was meticulously sourced from Yahoo Finance.
Selection Criteria: MSFT and SMSNG were rigorously selected based on their respective correlation values, representing stocks with high and low correlations.
Visualization: Data was methodically visualized through graphs, and daily returns were calculated using daily close price differentials.

**1st Data Science Task: Single Variable Stock Prediction**
Stock prices were predicted using a singular variable: Close.
Steps Undertaken:
1. Null-values were systematically eliminated.
2. Month/day/year values were isolated using the DateTime function in pandas.
3. Values were transformed into numpy arrays.
4. Data was accurately scaled, trained, and subsequently reshaped.
5. An LSTM model was meticulously crafted.
6. The model was compiled, trained, and datasets were partitioned for testing.
7. The testing data was reshaped.
8. Stock prices were then predicted.

Stocks Analyzed:
AAPL
MSFT
SMSNG

**2nd Data Science Task: Multivariate Stock Prediction using LSTM**
Stock prices were predicted employing multiple variables.
Sequential Steps:

1. Time series data was converted to supervised learning employing lag features.
2. Input and forecast sequences were designed, amalgamated, and any null values were discarded.
3. Features were normalized to attain a similar scale.
4. The data was reframed for supervised learning and superfluous prediction columns were expunged.
5. Data was partitioned into distinct training and testing sets.
6. Datasets were bifurcated into inputs and outputs.
7. Input data was reshaped into three dimensions.
8. The LSTM network's parameters, including epochs and batch size, were configured.
9. The network was trained with the datasets.
10. Results were illustrated using well-defined plots.
    
**Findings**

Comparative Analysis of Methods
**Single Variable LSTM:**
The method streamlined the stock prediction challenge.
It proved efficacious in predicting overarching trends (either up or down).
It was discerned to be more straightforward to implement compared to its multivariable counterpart.
**Multivariable LSTM:**
It incorporated a more extensive set of influencing factors, providing a realistic prediction.
Offered superior day-to-day price predictions.
Its construction was notably intricate compared to single variable LSTM.

**Conclusions and Recommendations**
Upon reflection, this project served as an insightful foray into stock price prediction using LSTM. If future endeavors build upon or replicate this initiative:
It would be judicious to consider additional factors influencing stock prices, such as quarterly earnings and broad market trends.
Anomalies and seasonal shifts, which significantly sway stock prices, must be given due consideration.
