# Predicting the price of Airbnb Listings in New York City
## Here is the link to the Tableau interactive dashboard [Tableau - AirBbB in NYC Analytics](https://public.tableau.com/app/profile/nguyen.ho2733/viz/Airbnb_16840158070070/Dashboard3)

## 1. Introduction to the data set

For the project, I use the [New York City Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) data set. This dataset features Airbnb listings in New York City, including 48,895 sample units with 15 variables:

- `id`: a unique identifier for each Airbnb listing
- `name`: the title of the Airbnb listing
- `host_id`: a unique identifier for each Airbnb host
- `host_name`: the name of the Airbnb host
- `neighbourhood_group`: the borough in which the listing is located 
- `neighbourhood`: the specific neighbourhood in which the listing is located 
- `latitude`: the latitude coordinate of the listing
- `longitude`: the longitude coordinate of the listing
- `room_type`: the type of room (entire home, private room, or shared room)
- `price`: the price for the listing per night
- `minimum_nights`: the minimum number of nights required for a booking 
- `number_of_reviews`: the total number of reviews for the listing
- `reviews_per_month`: the average number of reviews per month for the listing 
- `availability_365`: the number of days in a year that the listing is available for booking 
- `calculated_host_listing_count`: the number of listings of each Airbnb host

## 2. Data Exploration
<img width="1141" alt="Screen Shot 2023-05-14 at 10 19 46 PM" src="https://github.com/ChloeHo12/New-York-City-Airbnb-Price-Prediction/assets/98048503/4f2a70cc-ce0d-4338-b941-1852f40e9bd5">


## 3. Modelling
Followed by Data Preprocessing, I employed seven different models to predict the price of Airbnb listings in New York City. These models include Linear Regression with all predictors, Linear Regression with best subset variable selection, Decision Trees, Bagging, Random Forests, Boosting, and Support Vector Machine. 

## 4. Conclusion

The finding suggests that SVM is a reliable model for predicting the price of an Airbnb listing in the given dataset.
While SVM is the best overall performer, it is notable that the other models also demonstrate reasonable performance, with test RMSEs ranging from 207 to 239. 

It's important to consider the strengths and limitations of each model, as well as the specific needs and goals of the analysis. For example, linear regression with best subset variable selection is a simpler and more interpretable model, while ensemble models like random forests or boosting can capture complex interactions and nonlinear relationships between predictors. The choice of the best model ultimately depends on various factors, highlighting the need to carefully consider model complexity and interpretability when selecting a model for a specific analysis.
