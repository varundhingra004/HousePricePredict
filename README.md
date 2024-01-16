# HousePricePredict

Using the House Prices dataset of Kaggle, I wrote a housse price prdictor using Linear Regression.

There were around 80 features. Since there was data entered for most of the features, I used almost all of the features. Very few feature were dropped.
Missing values were filled with the mode value of each columns.

Individual features were plotted against the target - Sale Price using individual scatter plots. Most of the features had a Linear relationship.
All of the categorical features were One Hot encoded.

Training gave an R squared score of 0.92 to 0.95 which shows that Linear Regression was a good fit for the model.
