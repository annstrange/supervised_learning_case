## Case Study

Today we are going to use all the skills we have learned to tackle a real
problem in industry. The problem is churn prediction with a ride-sharing
company in San Francisco.  Since the data is sourced from a real company, we
ask you not to share the dataset. See more about the problem in
[group.md](group.md). 

# Data Preprocessing
We took a simple approach to our preprocessing and feature engineering steps.  We've outlined them below as follows:  
- Converted `last_trip_date` and `signup_date` to DateTime objects
- Filled NaN values with the means for the following columns:  
  - `avg_rating_by_driver`
  - `avg_rating_of_driver`
- Filled NaN values in the `phone` column with "Unknown"
- Converted string variables into dummy variables for the `phone` and `city` columns

# Feature Engineering
To take seasonlity and time of week or month into account we converted our `last_trip_date` into a multitude of date features, using the fastai library method `add_datepart`.  

# Random Forest Appraoch



# XG Boost Gradient Boosting

# Logisting Regression

# Recommendations to the Client

The features that seem to matter most are.... 

