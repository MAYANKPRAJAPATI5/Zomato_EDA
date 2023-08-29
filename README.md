# Zomato Exploratory Data Analysis (EDA) Project

![Zomato Logo](http://www.pngimagesfree.com/LOGO/Z/Zomato/Zomato-Logo-PNG-HD-Transparent.png)

Welcome to my EDA project on the Zomato dataset! In this project, I perform exploratory data analysis on the Zomato restaurant data to uncover insights and trends.



## Introduction
Exploratory Data Analysis (EDA) is a preliminary step of Machine Learning and is used extensively in this field. Although it is not necessary to perform EDA to build models, it is definitely recommended as it helps to know the data better. If performed correctly, it gives us insights that are not easy to witness directly.

In this notebook, I have performed a detailed analysis of the Indian Restaurants Dataset from Zomato. Following are the things that you will learn from this project:

1. Basic composition of data
2. Removing duplicates
3. Dealing with missing values
4. Understanding features
5. Plotting horizontal bar charts (multicolor)
6. Using group by, apply, and unique functions
7. Scatter plot
8. Word Cloud
9. Box plot
10. Drawing insights and conclusions from data 

## Dataset(Source- Kaggle)
Restaurant Dataset
This dataset contains information about various restaurants. It is organized with a total of 211,944 entries and 26 columns. Each entry corresponds to a restaurant and provides details about its attributes. Below is a brief overview of the columns in the dataset:

1. res_id: Unique identifier for each restaurant.
2. name: The name of the restaurant.
3. establishment: Type of establishment (e.g., cafe, fine dining, etc.).
4. url: URL of the restaurant's webpage.
5. address: Address of the restaurant.
6. city: City in which the restaurant is located.
7. city_id: Unique identifier for the city.
8. locality: Specific locality within the city.
9. latitude: Latitude coordinate of the restaurant's location.
10. longitude: Longitude coordinate of the restaurant's location.
11. zipcode: Postal code of the area.
12. country_id: Unique identifier for the country.
13. locality_verbose: Detailed description of the locality.
14. cuisines: Types of cuisines offered by the restaurant.
15. timings: Operating hours/timings of the restaurant.
16. average_cost_for_two: Average cost for two people dining.
17. price_range: Price range category.
18. currency: Currency used for pricing.
19. highlights: Special features or highlights of the restaurant.
20. aggregate_rating: Overall rating of the restaurant.
21. rating_text: Textual representation of the rating.
22. votes: Number of votes/ratings received.
23. photo_count: Count of photos available for the restaurant.
24. opentable_support: Opentable support availability.
25. delivery: Indicates whether the restaurant offers delivery (1 or 0).
26. takeaway: Indicates whether the restaurant offers takeaway (1 or 0).

Please note that the dataset contains various data types, including integers, floats, and objects (strings). Some columns may have missing values, as indicated by the "Non-Null Count" for each column.

This dataset provides valuable insights into different aspects of restaurants, including their locations, cuisines, pricing, ratings, and services. It can be used for exploratory data analysis, machine learning, and other analytical purposes.

