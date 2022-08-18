# Citi Bike Data Exploration 
## by Mustapha Adedayo Alude


## Dataset

The dataset includes information about individual rides made in a bike-sharing system covering the
New York City. In the dataset, we have 14 features and several observations (running to millions). 
The dataset can be found [here.](https://s3.amazonaws.com/tripdata/index.html), 
with feature documentation available [here](https://ride.citibikenyc.com/system-data)

While exploring the data, I discovered that for us to have a deeper insight to the project problem, 
the features provided wouldn't be enough. I had to take steps to engineered some new features I 
think would be intrumental in getting the insights needed. 

After much investigations and cleaning were done on the data, the final product had to be where some 
data points in the original dataset were removed due to them not having much to contribute to the 
investigation.

## Summary of Findings

The trip duration in the original dataset take on a very large range of values, 
from about 60 seconds at the lowest, to about 6 million seconds at the highest. 
But because more than 95% of the data is between 60 seconds and 4000 seconds,
I removed samples above 4000 seconds trip duration in our final dataset.

In the exploration, I found out that there was slight relationship between trip 
duration and other numerical variables. Trip distance seem to have the highest
relationship with trip duration when compared with numerical variable. This 
investigation was on all the dataset observations including some inconsistent
data points. However, when all the inconsistent data points were from the dataset, 
the was an improved relationship between trip duration and other numerical variable.
This confirm that there was negative relationship between trip duration and age of 
the riders: though this was not depicted through the scatter plot. 

It appears that more than 90% of the Citi Bike Users are Subscribers. The peak hours fall 
between 8:00-9:00 and 9:00-10:00 in the morning, and 17:00-18:00 and 18:00-19:00 in the evening. 
And riding activities happen more often during the weekdays. Summer months tend to be the
peak months during the year of review. 

The investigation confirmed that there was an upsurge of trip duration during the evening 
across gender classes. People tend to ride more during the weekends compare to weekdays
across all gender classes. Summer months contribute mostly to the trip duration during 
the year of reveiw. 

In conclusion, mostly, customer users always have the attributes of being an unknown gender 
and unknown age (0). There's high tendency of a user that have all these attributes to ride 
more with slight increasing in trip duration.


## Key Insights for Presentation

For the presentation, I focus on the factors that influence most for trip duration. 
I start by checking the distribution of trip duration together with other features
that are important for the presentation. 

Afterwards, I proceed to check the relationship of some features with target variable. 
I use scatter plot to visualise the relationship, then heatmap for correlation coefficient
values, and bar chart to plot features relationship using the correlation coefficient.

I conclude by relating the trip duration with come categorical and numerical features using 
pointplot.
