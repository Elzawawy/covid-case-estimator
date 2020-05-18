# Models Summary and Learnt Lessons
We mainly conducted three experiments:
*  Exponential model for daily cases per country
*  Neural network model for daily csaes per country
*  Neural network model for total cases for a given country
## Exponential model for daily cases per country
## Neural network model for daily cases per country
Regarding the credit assignent problem the main probelem faced was that the size data was small so that was a limitation for the model's
results. There was a trade off in this case as the weather data that is used to increase the number of features used was the limiting factor.
The weather data's size was small and if we wanted to increase the training data used, we had to elimante the features obtained from the 
weather data. This would have made us face another problem wich is the problem of relevnt factors. The weather data provides
features that are useful for training so we decided to continue using it with the penalty of less training data.
In order to check wether the model was good enough we tried two approaches. The first one was modelling the problem as 
a time series forecasting problem and using LSTM as the building block for our model. The second approach was using a fully connected 
neural network and modelling the problem as a regression problem. Both results were close with the fully conneced network preforming
slightly better. This is normal as the time series forcasting problem needs alot of data for the model to perform better. More
data would have better indicated the better model to use.

