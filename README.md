# Zindi-wins-AI4D-Predict-the-Global-Spread-of-COVID-19-insights
The codes presented here are available for downloads. They represent my winning solutions on Zindi.

The goal of the challenge was to predict covid 19 deaths for 209 countries ~ 2months into the future for April 18 2020 to June 8 2020.

Files have been uploaded here as follows
pdf- showing presentation of my approach , solution and insights
rmd files - 2 xgboost linear models and an ensemble of the xgboost models. All codes were written in R
csv - Files obtained from JHU git repo as at April 18 2020

To obtain recent csv files, complete the following steps:

In RStudio ;

Select File > New Project.., >select Version Control> Choose Git, then provide the repository HTTPS link,

HTTPS link is https://github.com/CSSEGISandData/COVID-19

select the R workspace folder and create the project. RStudio now copies (clone in Git terms) the content of the repository to your project folder.

To access the file, navigate to the location e.g. COVID-19/csse_covid_19_data/csse_covid_19_time_series/time_series_19-covid-Confirmed.csv'
