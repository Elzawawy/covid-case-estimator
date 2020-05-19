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
