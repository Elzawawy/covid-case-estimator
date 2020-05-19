# Data Used
In order to curate our own dataset, and features from multiple datasets, you face a problem. Each dataset you use has its own format and the shapes.
That's why for you own dataset you have to build you own format to cumbersome all the datasets under one umberella and make those features mergable throughout your work.

## Our Data Format
We save features in the form of `dicts`. **Dict is the Python's HashMap implementation**, where you have `K (key)` is the country and the `V (value)` is the feature. 
From each dataset we explore we curate the features we need in that format aiming for one unified dataset shape that can be merged on demand.

## Folders
You find four folders here each for a dataset, the four main datasets we explored as follows: 
* [Worldometers Daily Data](https://www.worldometers.info/coronavirus/) which is web-scrapped by David Bumbeishvili on his [Github](https://github.com/bumbeishvili/covid19-daily-data).
* [Our World In Data Coronavirus Dataset](https://ourworldindata.org/coronavirus) by OWID organization, also avaiable on [Github](https://github.com/owid/covid-19-data).
* COVID19 Global Weather Data by Pierre Winter on [Kaggle](https://www.kaggle.com/winterpierre91/covid19-global-weather-data).
* COVID-19 Country Data by Patrick on [Kaggle](https://www.kaggle.com/bitsnpieces/covid19-country-data).

In each folder, you will find the original dataset files, and also the files we curated as **feature-inpendent dicts**. These files collectively is the CCE dataset, which is the core of our work and the second contribution of this work to the world. 

**Note.** We use Pickle Files to save our `dicts` in order to preserve the object types by Serilization and Deserilization of objects.

## More Data resources we found interesting through the way (Might be helpful for anyone looking)

* [Weather Features Dataset](https://www.kaggle.com/giginghn/weather-features) by [giangnguyen](https://www.kaggle.com/giginghn) from kaggle.

* [Weather Data for COVID-19 Data Analysis](https://www.kaggle.com/davidbnn92/weather-data-for-covid19-data-analysis) by [Davide Bonin](https://www.kaggle.com/davidbnn92) from Kaggle.

* [COVID-19: current situation on May](https://www.kaggle.com/corochann/covid-19-current-situation-on-may) Notebook on Kaggle.

* [COVID-19: Digging a Bit Deeper](https://www.kaggle.com/abhinand05/covid-19-digging-a-bit-deeper) Notebook on Kaggle.

* [Google's COVID-19 Community Mobility Reports](https://www.google.com/covid19/mobility/). (Tune in later, we might try that on)

* [Forecasting the spread of the novel coronavirus](https://github.com/Nu-AI/Livid-About-COVID) github Repository that does similar work of ours.

* [Country Info Dataset](https://www.kaggle.com/koryto/countryinfo) by [My Koryto](https://www.kaggle.com/koryto) from Kaggle.

* [Covid19 Analysis: EDA + SEIR Model + Predictions](https://www.kaggle.com/giginghn/covid19-analysis-eda-seir-model-predictions) Notebook on Kaggle.

* [COVID-19 Lockdown dates by country](https://www.kaggle.com/jcyzag/covid19-lockdown-dates-by-country) by [jcyzag](https://www.kaggle.com/jcyzag) from Kaggle.

* [Covid Severity Forecasting](https://github.com/Yu-Group/covid19-severity-prediction) github Repository thats does similar work of ours but exposes their work as a Python library and is a great place to start from.

* [The Awesome Coronavirus Project](https://github.com/soroushchehresa/awesome-coronavirus), do I need to explain ?
