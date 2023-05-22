This is a Kaggle competition task I have selected for a portfolio project. I chose this task because it is related to my industry of public transport. Throughout my course, I have used everyday traffic congestion as a real-world example problem to discuss different machine learning topics.

The Kaggle task is to predict congestion based on an aggregate measure of stopping distance and waiting times at intersections in four major US cities: Atlanta, Boston, Chicago, and Philadelphia.

The data consists of aggregated trip logging metrics from commercial vehicles, such as semi-trucks. The data has been grouped by the following factors:

Intersection

Month

Hour of day

Direction driven through the intersection

Whether the day was on a weekend or not

For each grouping in the test set, we need to make predictions for three different quantiles: the 20th, 50th, and 80th percentiles for the following metrics:

The total time stopped at an intersection
The distance between the intersection and the first place a vehicle stopped while waiting
The data was downloaded from https://www.kaggle.com/competitions/bigquery-geotab-intersection-congestion/overview.

First, we will perform data analysis, followed by data processing and feature engineering. Then, we will try different types of regression models. Later, we will select a model with the minimum root mean square error value and fine-tune its hyperparameters to further improve model performance.
