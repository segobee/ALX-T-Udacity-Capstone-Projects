# TMDb Movie Data Analysis


## Dataset

The dataset contains movies data on TMDb platform. In the dataset, we have 21 features and 10866 observations from The Movie Database.

The dataset and feature explaination can be found [here](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

The target, which is the profit, was derived by subtracting budget from revenue

**Note:** The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

## Summary of Findings

I analysed this dataset in two segments; (i) numerical (ii) categorical

In terms of numerical analysis, we saw that only popularity and vote_count are to be considered when making film recommendation to investor. They performed better in terms of correlation to profit. 

In terms of categorical analysis, I focused on only three features. They are;

    - Genres 
    - Month 
    - Day
Genres Feature
- The following are to be recommended:

    - Action
    - Adventure
    - Animation 
Month Feature
- The following are to be recommended:
   - June
   - July 
   - May
   - November
   - December 
   
Day Feature 
- The following are to be recommended:
    - Monday
    - Thursday
    - Tuesday
    - Wednesday

## Limitations

There are couple of limitations in the data: 
- Some independent variables (categorical) that could have provided much insight in relation of their correlation to profit could not be determined as engineering them to numerical variable is outside the scope of this project 
- I do not have a lot of detail to draw conclusion about engineered features (release days and months) on how effective they would be when considered.
- The categorical variable are not evenly distributed. Which says that, there are some categories in data that are more represented than the other.
- Also, the numerical features do not have strong correlation to the target variable