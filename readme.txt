Programming languages

This function is processing by usiong python 3.7

Function Packages

pandas, numpy, sklearn, xgboost, datetime

Data Processing

Hong Kong historical weather and holiday is added into the training dataset. 
The data file names are hkwaether.csv and hkholiday.csv respectively.
In test.csv and train.csv, the column of day and time is formed from the column of date
The time is converted into cyclical mode, which is sine and cosine function
The code is used XGBRegressor to predict the test.csv
The parameter of the model is {max_depth=5, learning_rate=0.1, n_estimators=1000, silent=True, objective='reg:gamma'}