# LSTM Price Prediction for Nifty 50 stock     
- This Code Uses nifty 50 stock historical prices from 2015 till 2024 using minute intervals    
**NOTE: I had to use low sequence numbers , low LSTM Layers , low epoches and low future_len 
If you have better memory and GPU change these values to what i commented in front of them**    
- It uses ModelCheckpoint and ReduceLROnPlateau as callbacks     
**Don't Try EarlyStopping**     
Any help would be appreciated to optimize it    
The Results i got with current values in code . Hope you get better ones with the values provided    
**Overall MSE: 0.025405116382271893**        
![download (5)](https://github.com/user-attachments/assets/246329ef-b200-4b41-b95b-eb682b92f431)
