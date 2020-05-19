# Part 2: Building COVID-19 Cases Estimator Models

![](https://slidesgo.com/storage/76840/3-covid-19.png)

We built differnet models with different approaches. **We mainly conducted three experiments:**
*  Exponential model for daily cases per country
*  Neural network model for daily csaes per country
*  Neural network model for total cases for a given country

Each experiement is conducted in a **seperate notebook.** And in each notebook, we present th data used for model, a berif about the model we are using and finally the training and testing results of the model.

## Models Summary and Learnt Lessons

## Exponential model for daily cases per country
The Exponential Model is a simple yet naive model, that is because it only accounts for time as feature. Whereas, a lot of features can share an importance for the spread of COVID-19 not only time. 

It assumes that simply increasing time means increase in cases. Which, is not the current case as we see some countires have worked its way to maintain a daily number of cases less than their peak. The results reflected this and the loss wasn't that low. 
There was no credit assignment problem met during this expriment to solve.

**Learnt Lessons:**
* An exponential model based on time feature only isn't reliable enough, but works well as a basline model.

## Neural network model for daily cases per country
Regarding the credit assignment problem the main probelem faced was that the size data was small so that was a limitation for the model's results. 
There was a trade off in this case as the weather data that is used to increase the number of features used was the limiting factor. The weather data's size was small and if we wanted to increase the training data used, we had to elimante the features obtained from the weather data. 

This would have made us face another problem wich is the problem of relevant factors. The weather data provides
features that are useful for training so we decided to continue using it with the penalty of less training data.
In order to check if the model was good enough we tried two approaches. The first one was modelling the problem as 
a time series forecasting problem and using LSTM as the building block for our model. The second approach was using a fully connected neural network and modelling the problem as a regression problem. Both results were close with the fully conneced network preforming slightly better. 

This is normal as the time series forcasting problem needs alot of data for the model to perform better. More data would have better indicated the better model to use.

**Learnt Lessons:**
* Working with multiple features not only time improves a lot over our baseline model and reduce naive estiamtion (one that is based on time only).
* Working with Time Series Data Forecasting is promising but needs more data to acheive more.
* Weather Features are very relevant in context of daily cases.
* Daily Deaths and Recovered Cases were also of good importance to the daily number of cases.



