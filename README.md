# Rain-Prediction-in-Australia

# Introduction
Global warming affects the ecosystem and the human communities across the globe are losing
natural resources and cultural significance. Australia is one of the worst-hit countries that is
experiencing high temperatures, rising sea levels, coral bleaching in The Great Barrier Reef and
unseasonal rain. One such example is the “Black Summer” bushfire in 2019 where more than 55
million acres of land were burnt. However, food security is a major issue caused by climate
change. Agriculture largely depends on rain and hence its forecast becomes imperative. This
project mainly focuses on the prediction of rain the next day. Rain tomorrow is the target variable
of the data. Multiple attributes like Temperature, Windspeed, Humidity, and Pressure are
considered to predict the rain on the next day. The information in the dataset is gathered from
automated equipment from various weather stations. The goal of the project is to build an
efficient classification model which would help in building budget-wise rainfall forecast
applications.

#  Dataset
The Dataset we used for predicting the rainfall prediction in Australia from Kaggle. This dataset
consists of 23 features and 145461 rows. The “RainTomorrow” attribute is considered the target
variable. Below is the list of features and their descriptions:
1. Date: -The date of observation
2. Location: -The name of the location of the weather station
3. MinTemp: -The minimum temperature in degrees Celsius
4. Max Temp: -The maximum temperature in degrees Celsius
5. Rainfall: -The rainfall recorded for the day
6. Evaporation: -The evaporation (mm) during the day
7. Sunshine: -The number of hours of sunshine in the day
8. WindGustDir: -The direction of the wind gust
9. WindGustSpeed: -The speed of the wind gust
10.WindDir9am: -Direction of wind at 9am
11.WindDir3pm: -Direction of wind at 3 pm
12.WindSpeed9am: -Wind speed at 9am(km/hr)
13.WindSpeed3pm: -Wind speed at 3pm(km/hr)
14.Humidity9am: -Humidity at 9 am
15.Humidity3pm: -Humidity at 3 pm
16.Pressure9am: -Atmospheric pressure at 9 am
17.Pressure3pm: -Atmospheric pressure at 3 pm
18.Cloud9am: - Fraction of sky obscured by cloud at 9 am
19.Cloud3pm: - Fraction of sky obscured by cloud at 3 pm
20.Temp9am: - Temperature (degree celsius) at 9 am
21.Temp3pm: -Temperature (degree celsius) at 3pm
22.Rain Today: -Did, did it rain today?
23.Rain Tomorrow: -Target variable (Did it rain Tomorrow?)

#  Proposed Analytics Solution
1. Gathering data: For the project, we looked at a variety of online data sources before settling on a
Kaggle dataset with many of the features mentioned above for rainfall prediction.
2. Data Analysis: : In the first stage, we analyze the data to better understand each element of the
dataset, which allows us to better comprehend the data and identify important features and trends that
could be beneficial in model building.
3. Data Preprocessing: : Through the data analysis step, we will handle the data quality issues using
different approaches suitable for the issue (such as imputation for missing values and clamp
transformation for outliers).
4. Feature Selection: Selecting the features and implementing dimensionality reduction using Chi
square test, PCA and Recursive Feature Elimination methods.

# CONCLUSION
In conclusion, we have used Multiple classification machine learning models to predict the rain in
Australia. We have performed all the pre-processing steps -Normalization, Transformations, Handled
missing values, and Outliers. After pre-processing, we used this pre-processed dataset to implement our
machine learning models. In this project, we have Implemented seven machine-learning algorithms to
predict the rainfall and used nine metrics Sensitivity, Specificity, Precision score, Recall, F-measure,
Discriminant power balanced, Classification Rate, Geometric Mean, Youden's Index to evaluate the
performance of each of our models. Among the algorithms implemented, we observed that the
XGBoost classifier performed the best and Naive Bayes showed the least efficiency on our dataset. So
XGBoost classifier can be used to predict the rainfall the next day, and it would help build budget-wise
rainfall forecast applications.

