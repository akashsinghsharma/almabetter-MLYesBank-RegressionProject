# almabetter-MLYesBank-RegressionProject
This is 2nd capstone project for AlmaBetter School. 

Share market is simply the market place where multiple traders and investors buy and sell shares of different companies. The primary crux of share market is that people try to buy share in a lower prce and sell it when the price increases, thus marking a profit. 

In the data set I recieved, I have features of open, high, low and close, where I  had to find a pattern to predict the close using open, high and low. 

I started my analysis with EDA, where I found how exactly the data was distributed. Independent parameters were skewed, so I adjusted them with log transformation. 
I also made plots to see how the dependent variable was varying with different independent variables.

I also made a dataframe for VIF score, even when the vif was high, I decided not to drop any feature to see the accuracy I get. (Note: I later decided not to drop any feature finally as I am getting a high accuracy). 

I started building the models, I used LR, Ridge and Lasso and also XGBRegression. I got the highest accuracy in XGBRegression with least mean squared error. Thus, I am selecting XGBRegression as my final model with 0.991 Rsquare. 
