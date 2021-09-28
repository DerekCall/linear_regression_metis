# Predicting Board Game Complexity

 My goal is to find the determinants of the weight (complexity) of a board game, and to create a predictive model based on those findings. I scraped data from boardgamegeek.com and have cleaned the data to allow for OLS regression analysis:
 
 ![](https://github.com/DerekCall/linear_regression_metis/blob/main/Screen%20Shot%202021-09-28%20at%205.14.03%20PM.png?raw=true)
 
I will continue to verify if a simple regression model will be most appropriate for this data set. If a Ridge or Lasso model gives a higher r-squared value we will continue with that model on the test data. 

This preliminary analysis has shown that the current rating of the game affects the predicted complexity the most. Other important features are the type of the game and maximum estimated playing time from the manufacturer. 


