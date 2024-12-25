# Linear Regression Case Study
> This is a case study to build a multiple linear regression model for the prediction of demand for shared bikes.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
BoomBikes, a US bike-sharing provider, aims to predict the demand for shared bikes post-Covid to boost revenue post-pandemic. They have gathered a dataset on daily bike demands in the American market to understand the factors influencing bike demand. The business goal is to model bike demand using independent variables to adjust business strategies and meet customer expectations.


## Conclusions
- We built a linear regression model lr1 to predict the bike sharing count.
- R-squared of the model: 0.834
- R-squared of the test data: 0.809
- `cnt = 2015.9015 * yr - 557.7596 * holiday + 422.7937 * weekday + 162.5193 * workingday + 4288.2546 * temp - 1073.4476 * hum - 1564.5809 * windspeed - 644.9492 * Spring + 377.0228 * Summer + 786.0812 * Winter - 2167.2031 * LightRain - 509.4176 * Mist + 2159.4744`

## Technologies Used
- Python
- Pandas
- Numpy
- Matplotlob
- Seaborn
- Statsmodels
- SKLearn

## Acknowledgements
- This project was based on Linear Regression module of [Executive Post Graduate Programme in Machine Learning & Artificial Intelligence](https://www.iiitb.ac.in/executive-post-graduate-programme-in-machine-learning-artificial-intelligence).



## Contact
Created by [@krantisinh](https://github.com/Krantisinh/)
