# Revzilla

Linear Model is the form of supervised learning, in which we feed the model/algorithm set of attributes called dependent variables and dependent variable which we need to predict. Initially, we provide independent and their corresponding dependent variable to train the model. The basic idea is to obtain best fit line along our datapoints and best fit line is which has minimumm sum of distance between datapoints to our regression line. Basic equation for linear model can be defined as Euclidean dot product between 2 vectors: where 'w' is the weight vector and 'x' is the input vector.
LSTM (Long Short-Term Memory network) is a type of recurrent neural network capable of remembering the past information and while predicting the future values, it takes this past information into account. LSTM networks are well-suited to classifying, processing and making predictions based on time series data, since there can be lags of unknown duration between important events in a time series. This is important in our case because the previous sales data is crucial in predicting its future sales.


## CONCLUSION


We will use historical data to identify any key trends in the business, as well as develop a sales forecast to set goals for the marketing teamsusing some statistical approaches.

First of all we read the data and try to visualize the data without applying any algorithm. Then, preprocess the data- checks the correlation between the attributes, handling the missing value, and checked the normalization of the data to  scale all the attributes to get better prediction value. We then split our datasets into training and test sets. We feed our algorithm with training sets and further analyze its prediction on test set with actual values. For the accuracy we calculated the Adjusted R squared. Finally, we plot the predicted value with actual value and observed how much is the difference between our actual and predicted values.

<b> 3a - Explain which method you chose and why?</b>  
<b> 3b - Explain how you evaluated your results?</b>                         
<b> 3c - Summarize the accuracy of the forecast?</b>  

We applied our algorithm on the complete dataset we get, but further when try to improve our model with removing some less important column from our dataset, we observe deviation from the model we get on complete dataset. Both the regression shows positive response.So to obtain best model, we have to take care of each part like preprocess the data completely, understand the importance of each attribute with our target attribute. Filter out the data which can affect our data and keep the necessary attributes.

I have applied both Linear Regression and LSTM to create the sales forecast and to check which models performs better for our dataset. For Linear Regression model, we calculated Adjusted R-squared to check our model accuracy or how our model is perfoeming better. We get the Adjusted R-squared as 62% for our model. Another model that I used is LSTM. Initially, I calculated the predictions on y_test set which was approximately at 91%. Based on my evaluation I am chosing LSTM for my dataset as it the prediction for this model is 91% which is higher than linear regression. LSTM is capable of remembering the past information and while predicting the future values, it takes this past information into account. This is important in our case because the previous sales data is crucial in predicting its future sales.

<b> Improvements </b> 

One improvement we can do for this model is to add holidays, breaks, and other seasonal effects. They can be simply added as a new feature. By using this model, we have our baseline sales predictions
