# Zomato Restaurant Data Analysis Report

# Introduction
The Zomato dataset contains restaurant-related information across various countries. This report aims to analyze key insights from the dataset, focusing on the distribution of data, ratings, cuisines, and more. The dataset contains 9551 rows and 21 columns. We will explore missing data, trends, and key statistics related to restaurant ratings, country-wise distribution, and other factors.

# 1. Dataset overview
Dataset Dimensions:
- 9551 rows and 21 columns

Columns:
- Restaurant ID, Restaurant Name, Country Code, City, Address, Locality, Longitude, Latitude, Cuisines, Average Cost for two, Currency, Rating, Votes, and more.

Missing Data:
The dataset contains some missing data:
- The Cuisines column has 9 missing entries.
- Other columns are fully populated, indicating no missing values except the "Cuisines" field.

Data Type Inspection:
The data types are as follows:
- Integer and float types for numerical columns (e.g., Restaurant ID, Average Cost for two, Votes).
- Object type for categorical fields (e.g., Restaurant Name, Country, Cuisines).

# 2. Country-wise distribution
Top Countries Using Zomato
A pie chart visualization shows that India leads the list with the highest number of restaurants on Zomato, followed by the United States and the United Kingdom.

Observation:
- India accounts for 94.39% of the total records.
- United States contributes 4.73%.
- United Kingdom represents 0.87%.

# 3. Rating analysis
Distribution of Ratings
The ratings are categorized as follows:
- Excellent (4.5–4.9): The highest ratings received, with 95 restaurants rated at 4.5 and 61 restaurants rated 4.9.
- Very Good (4.0–4.4): Includes ratings from 4.0 to 4.4, where 144 restaurants were rated 4.4.
- Good (3.5–3.9): A significant portion of the ratings fall in this range, indicating a general satisfaction level.
- Average (2.5–3.4): Majority of the ratings fall within this range.
- Poor (1.8–2.4): A smaller portion, but still notable, rated below average.

Key Insights:
- A large number of ratings are in the "Not Rated" category (0.0).
- The average rating range (2.5–3.4) contains the highest count of reviews.

Rating Count by Color:
- Red: Poor (1.8–2.4) ratings are in this category.
- Orange: Average ratings.
- Yellow: Good ratings.
- Green: Very good ratings.
- Dark Green: Excellent ratings.

A bar chart visualizes the rating distribution by color, showing a concentration in the "Average" and "Good" ranges.

# 4. Restaurant Distribution by City
The restaurant distribution across cities shows that New Delhi accounts for the highest number of restaurants, followed by Gurgaon and Noida. The concentration of restaurants in these cities suggests they are the major hubs in India for Zomato.

Key Insights:
- New Delhi: 68.87% of the records
- Gurgaon: 14.07% of the records
- Noida: 13.59% of the records

# 5. Online delivery avail or not avail?
Countries Offering Online Delivery
- India has the largest share of restaurants offering online delivery, with 2423 restaurants listed.
- United Arab Emirates (UAE) has a significantly lower count, with only 28 restaurants offering delivery.

Observation:
- Online delivery is much more common in Indian restaurants compared to other countries, suggesting a stronger trend for online food ordering in India.

# 6. Countrie interested in most Cuisines 
The dataset includes a wide variety of cuisines, but the most commonly listed cuisines include:
- Indian
- Chinese
- Italian
- American

These cuisines make up the largest portion of restaurant offerings, indicating the diverse food preferences in the regions represented in the dataset.

# 7. Currency and price details
Currency Distribution:
- Most restaurants use Indian Rupees (INR), aligning with the large percentage of restaurants located in India.
- Other common currencies include USD (United States Dollar), AED (United Arab Emirates Dirham), and GBP (British Pound).

# 8. So i could find out...
- India is by far the leading country for restaurant data on Zomato, with a high concentration of restaurants offering online delivery.
- A significant portion of restaurants are rated average, indicating there’s room for improvement in overall quality.
- The UAE and United States have much smaller shares in comparison, suggesting that Zomato's reach in these countries is more limited.

# 9. Recommendations
- Encourage More Ratings: Many restaurants lack reviews or ratings. Promoting customer feedback can provide more accurate insights into restaurant quality.
- Expand Delivery Options: Zomato can further expand online delivery in countries like the UAE and the United States to capture a larger market share.
- Highlight Top-Rated Restaurants: Focusing on top-rated restaurants (Excellent category) can drive higher customer satisfaction and promote quality dining experiences.

