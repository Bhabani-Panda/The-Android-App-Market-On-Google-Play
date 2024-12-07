# The Android App Market On Google Playstore
![pic](https://github.com/user-attachments/assets/e3e08459-5c91-407f-b27f-efe36fe61ed6)

**Overview**\
This project involves a comprehensive analysis of the Android app market, specifically focusing on apps available on Google Play. With over 10,000 apps from various categories, the goal of this analysis is to uncover valuable insights that can help in devising strategies for app growth, retention, and monetization.

The dataset includes two primary files:
1.	apps.csv: Contains details about apps in the Google Play Store, with 13 features that describe each app.
2.	user_reviews.csv: Contains 100 pre-processed reviews for each app, with sentiment analysis attributes including sentiment polarity and subjectivity.

The analysis covers the following areas:\
•	Data cleaning and preparation\
•	Correcting data types for essential features like Installs and Price\
•	Exploring app categories and their market share\
•	Examining app ratings, size, price, and the relationship between these features\
•	Sentiment analysis of user reviews
________________________________________

**Key Objectives**\
•	***Data Cleaning:*** Prepare the dataset by removing special characters like commas and dollar signs, ensuring numerical features such as Installs and Price are correctly formatted.\
•	***Data Analysis:***\
o	Explore the distribution of apps across different categories.\
o	Analyze the performance of apps based on their ratings.\
o	Investigate the correlation between app size, price, and ratings.\
o	Compare paid vs free apps and analyze their reviews.\
•	***Insights:***\
o	Discover which categories dominate the market and which have the fewest apps.\
o	Identify how app size and price affect ratings.\
o	Analyze the sentiment of user reviews and the difference between paid and free apps.
________________________________________

**Data Preparation and Cleaning**\
The cleaning steps focus on:\
•	***Removing special characters:*** Clean the Installs and Price columns to retain only numeric values by removing characters like commas, plus signs, and dollar signs.\
•	***Correcting data types:*** Convert Installs and Price columns into numeric types to facilitate mathematical operations and analysis.\
•	***Cleaning user reviews:*** Preprocess reviews by extracting sentiment-related features (Sentiment, Sentiment Polarity, and Sentiment Subjectivity).
________________________________________

**Data Analysis**
1. ***App Categories***
•	Identify the most common app categories in the dataset (e.g., Family, Games, Tools, etc.).\
•	Explore the share of each category in the market.\
2. ***Distribution of App Ratings***\
•	Analyze the distribution of app ratings across categories, with an average rating of 4.17.\
•	Visualize the ratings with a histogram to identify trends.\
3. ***App Size and Price***\
•	Investigate how the size and price of an app affect its rating.\
•	Examine whether users prefer lightweight apps or apps with higher prices.\
4. ***Relation between Category and Price***\
•	Explore how different categories of apps price their offerings, noting that Medical and Family apps tend to be more expensive.\
5. ***Filtering Junk Apps***\
•	Filter out "junk" apps, which are expensive but lack real functionality (e.g., apps created for novelty or testing purposes).\
6. ***Paid vs Free Apps***\
•	Compare the popularity (in terms of installs) and ratings of paid vs free apps.\
•	Analyze how pricing strategies affect app success.\
7. ***Sentiment Analysis***\
•	Perform sentiment analysis on user reviews to understand the general sentiment (positive, neutral, negative) towards apps.\
•	Compare the sentiment polarity of reviews for free vs paid apps to assess app quality.
________________________________________

**Key Findings**\
•	Category Distribution: Family and Game apps dominate the Google Play Store, followed by Tools, Business, and Medical apps.\
•	App Ratings: The majority of apps are highly rated, with an average rating of 4.17.\
•	App Size and Rating: Apps between 2 MB and 20 MB generally receive the highest ratings.\
•	App Price and Rating: Most apps are priced under $10, with Medical and Family apps being the most expensive.\
•	Paid vs Free Apps: Paid apps have a relatively lower number of installs compared to free apps, but their reviews are generally more positive.
________________________________________

**Conclusion**\
This analysis provides insights into the Android app market, focusing on critical factors like app ratings, size, price, and sentiment. Developers and companies can use these insights to make informed decisions about app development, pricing, and marketing strategies. Whether creating a new app or optimizing an existing one, these findings can help drive growth and user retention.
________________________________________

**Requirements**\
To run this project locally, you need the following Python packages:\
•	pandas\
•	matplotlib\
•	numpy\
•	seaborn
