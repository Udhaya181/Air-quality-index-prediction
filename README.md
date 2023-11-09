This project aims to analyze the Air Quality Index (AQI) of India and understand the
functions of various prediction models (such as linear regression, logistic regression, etc.). The
Air Quality Index (AQI) is a metric used to measure the air quality in a specific area. It is a
numerical value that reflects the concentration of pollutants in the air and how they may affect
human health. The AQI is calculated based on measurements of pollutants such as
1) ground-level ozone,
2) particulate matter,
3) sulfur dioxide,
4) nitrogen dioxide
5) carbon monoxide.
The purpose of AQI is to warn people about the air they are living in and also letting them
know which group of people might get affected by the air and also measures that an individual
can take to prevent submission to air pollution. The AQI measures is done by the prediction of
the data. Predictions of data can be achieved by using the machine learning algorithms.
Machine learning is a field of science where it builds training algorithms to understand the
patterns in data and make possible decisions.
This project is about comparing various supervised machine learning algorithms and selecting
the most accurate algorithm for the prediction of AQI with help of "Air quality index in India
(2015-2020)" data set. For predictions we select the four different models are Random
forest(City_day), Linear regression(City_hour), Logistic regression(Station_day),
Decision tree(Station_day), By Using this model we finalize the best fit model for the AQI
prediction with the calculation of metrics which model having the lower MAE, lower RMSE
and higher r-squared error and evaluating in different ratio of test & train sets. The AQI is
typically measured on a scale from 0 to 500, where higher values indicate poorer air quality.
