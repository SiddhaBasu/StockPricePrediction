# StockPricePrediction
Analyzes and forecasts Microsoft's stock prices using Python and LSTM neural networks on Yahoo! Finance’s massive dataset

* Processed Microsoft's stock price data since 1986 taken from Yahoo! Finance's dataset of Microsoft with pandas, creating functions to define windows of dates for the purpose of splitting the dataset
* Divided the dataset into training, validation, and testing, with a split of 80/10/10, in that respective order
* Added the validation set for the purpose of tuning hyperparameters in the neural network
* The neural network included 1 Long Short Term Memory (LSTM) layer, 2 hidden Dense layers, and 1 node as output. Trained for 100 epochs
* Below, you can see the similarity in prediction and observation stock prices through the graphs

![image](https://github.com/user-attachments/assets/1252496c-1079-48f6-81bb-5d3f8da764b4)

![image](https://github.com/user-attachments/assets/68a7245e-1f7e-4d8f-a5a2-55b85e56fa06)

![image](https://github.com/user-attachments/assets/fee7b928-6504-4383-a932-5e4a1ae4e491)

![image](https://github.com/user-attachments/assets/561d8b38-3cbf-4dda-a743-5e20271f6da3)

![image](https://github.com/user-attachments/assets/3a6243e4-96fb-42b8-a6f6-6415b4c7149a)
