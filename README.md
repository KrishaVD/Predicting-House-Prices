# Predicting-House-Prices

In this project, I wanted to predict the House Prices using the Linear Regression model from ML. I recognsied that the data had huge amounts of misisng data values. Since there were a lot of features in the dataset, I dceided to drop some features such as 'Alley', 'PoolQC', 'Fence', 'MiscFeature','GarageYrBlt','Id' as these had little correlation with the sale price and for the other missing values, I had replaced them with mean or mode values.

It surely took me a lot of time in cleaning and procesisng the data and I was using the sns heatmap graph along the way to check the remaining missing values. 

Then I split the data using the train_test_split function and after fitting the training data into the regression model, I calculated the r2 which tells us the difference between the actual and the predicted sale price. I used matplotlib to draw a graph right at the end to visualise the regression model. 

