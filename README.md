
## Predictive Model for Airbnb Pricing in Asheville, NC

#### Introduction:

In this analysis, we aimed to create a predictive model for Airbnb pricing in Asheville, North Carolina. Our goal was to assist new hosts in setting competitive prices for their listings. The dataset used for this analysis contains information about Airbnb listings in Asheville.

**Basic Data Information**:

Sample size:\
The dataset contains a total of 3,239 Airbnb listings in Asheville, North Carolina.\
There are 75 columns in the dataset, each representing different attributes of the Airbnb listings.

**Methods**:

For this analysis, we chose to use a regression model. We selected this model because it allows us to understand how different factors, such as the number of bedrooms, bathrooms, distance to downtown, and other features, influence the listing price.

**Variables Included in the Model**:

1.  Bedrooms: The number of bedrooms typically affects pricing directly.
2.  Bathrooms: The number of bathrooms can also impact pricing, adding convenience and luxury.
3.  Distance to Downtown: Proximity to downtown can increase pricing for better accessibility.
4.  Room_type : Entire rooms / apartments are highly priced than private rooms
5.  Amenities (Pool , Pets_allowed ,Kitchen) : Added Amenities comes with extra pricing.
6.  accommodates : Larger capacity listings comes with larger pricing.
7.  Beds : Directly Affects pricing as more beds accomodates more people
8.  Reviews(reviews_per_month, calculated_host_listings_count, review_scores_value,
9.  number_of_reviews_l30d) : Positive and higher reviews often result in higher pricing.

#### Results:

1.  We observe that our pricing is significantly influenced by several factors, including numbe of bedrooms, Room_type, Bathroom, DistanceTo Downtown, the presence of amenities like a pool and a kitchen, Accomodates, Reviews_per_month, Number of reviews in the last month, availbility through out the year, minimum stay requirements.

2.  Collecting the valuable data from new hosts is essential for enhancing our pricing model.

3.  Our model achieves a R-Squared of 0.53. For an apartment of room_type "Entire home/apt" that accommodates 4 with 2 Bathrooms and 2 bedrooms with 2 beds booked for 2 minimum nights and having 50 reviews with score value of 4.1 host total listings as 24, reviews per month as 50, distance to downtown as 1.1 , no pool and no pets allowed and no kitchen would give a price of $6,773. 

#### Conclusion:

1.  Our result concludes that, with the data provided, we can understand more than half of what drives pricing in Airbnb listings. However, there's still some remaining uncertainity which could be improved.

2.  Additional data taken from hosts such as recent any Nearby Attractions, or any local events or any seasonal trends can further help in improving the model.

