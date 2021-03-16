# Bulldozer-Price-Prediction
Predict the sale price of bulldozers sold at auctions based on it's usage, equipment type, configuration, and previous examples of how much similar bulldozers have been sold for.

Evaluation metric is RMSLE (root mean squared lot error) between the actual and predicted auction price
Train.csv contains data through the end of 2011
Valid.csv contains data from 1/1/2012-4/30/2012
Test.csv contains data from 5/1/2012-11/30/2012
Key fields in training set:

SalesID: unique identifier of the sale
MachineID: unique identifier of a machine. A machine can be sold multiple times
saleprice: what the machine sold for at auction (only in train.csv)
saledate: date of the sale
