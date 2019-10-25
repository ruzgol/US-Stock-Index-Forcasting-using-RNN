# US-Stock-Index-Forcasting-using-RNN
# Disclaimer:  This is not how trading works. 
Although the results of this work are very promising for the task of forecasting the future price of a single stock,
the keen reader should bear the following fact in their mind. Successful trading is all about balancing portfolios and minimizing the risk.
A Machine Learning practitioner should try to find and buy undervalued securities (stocks, bonds, and such) and sell the overpriced ones. 
# Abstract
Efforts are made towards the longterm (365-day) prediction of the close price index of DOW Jones Industrial index, using a 3-year window
form 2016 to 2019. This is a very interesting choice of data since it can put our ML algorithm to the test. In this window, during the 
test period, the index mostly shows an upward trend. There however exists a sudden drop In the test part. Its shown that a combination of
a convolution layer (to capture the patterns) and LSTM layers (for the sake of long memory) does a phenomenal job and the model is able to
accurately predict the 9-day moving average graph.
