# Model Card


## Model Description

**Input:** Describe the inputs of your model 
The data consists of aggregated trip logging metrics from commercial vehicles, such as semi-trucks. The data have been grouped by :

    intersection
    month
    hour of day
    direction driven through the intersection
    whether the day was on a weekend or not


**Output:** Describe the output(s) of your model
Total time stopped at an intersection, 20th, 50th, 80th percentiles and Distance between the intersection and the first place the vehicle stopped and started waiting, 20th, 50th, 80th percentiles

**Model Architecture:** Describe the model architecture you’ve used
A random forest regressor fine tune to provide minimun root mean squre error
## Performance

Give a summary graph or metrics of how the model performs. Remember to include how you are measuring the performance and what data you analysed it on. 

## Limitations

Outline the limitations of your model.
This model limited to data provided by telemetric system. if we use data from outside elements like weather etc we may get better results.

## Trade-offs

Outline any trade-offs of your model, such as any circumstances where the model exhibits performance issues. 
