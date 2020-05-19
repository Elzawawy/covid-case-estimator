# Part 1: Datasets Exploration 

The most prevelant problem that appears when a **new data science exploration task** appear as understanding the COVID-19 exploration task is **finding & collecting datasets for it**.

![](https://miro.medium.com/max/1200/1*GRHR16nydMdpADOi5MIk_w.jpeg)

And lucky for us, we found a lot of interesting datasets that we can work on to **curate our own datasets** for the task in hand.
Out of all datasets we found, we were particulary interested in the **five** datasets below:

* Novel Coronavirus (COVID-19) Cases, provided by JHU CSSE available on [Github](https://github.com/CSSEGISandData/COVID-19) and their awesome [Visualization Tools](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6).
* [Worldometers Daily Data](https://www.worldometers.info/coronavirus/) which is web-scrapped by David Bumbeishvili on his [Github](https://github.com/bumbeishvili/covid19-daily-data).
* [Our World In Data Coronavirus Dataset](https://ourworldindata.org/coronavirus) by OWID organization, also avaiable on [Github](https://github.com/owid/covid-19-data).
* COVID19 Global Weather Data by Pierre Winter on [Kaggle](https://www.kaggle.com/winterpierre91/covid19-global-weather-data).
* COVID-19 Country Data by Patrick on [Kaggle](https://www.kaggle.com/bitsnpieces/covid19-country-data).

We made **four notebooks**, each notebook is to explore a specific dataset (except the first one since its the same as the second mainly) and curate what we need from it.
Our Exploration steps are downloading, reading, understanding dataset and finally choosing the features we need out of it. In each notebook, we finalize by extracting the appropriate features into dictionary objects to be used later on by the models.
