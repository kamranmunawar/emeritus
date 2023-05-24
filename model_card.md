# Model Card


## Model Description

**Input:** Describe the inputs of your model 
>The data consists of aggregated trip logging metrics from commercial vehicles, such as semi-trucks. The data have been grouped by :
    intersection
    month
    hour of day
    direction driven through the intersection
    whether the day was on a weekend or not


**Output:** Describe the output(s) of your model
>The model makes predictions for three different quantiles of two different metrics covering how long it took the group of vehicles to drive through the intersection. The 20th, 50th, and 80th percentiles for the total time stopped at an intersection and the distance between the intersection and the first place a vehicle stopped while waiting. 

**Model Architecture:** Describe the model architecture you’ve used
>A random forest regressor fine-tuned to provide minimal root mean square error
## Performance
>I am using RMSE (root mean square error) as a performance metric for our model. Data is already divided into train and test datasets. we will use train data set to train our model and then use a test dataset to measure its RMSE value.

## Limitations

Outline the limitations of your model.
>This model is limited to data provided by a telemetric system. if we use data from outside elements like weather etc we may get better results.


