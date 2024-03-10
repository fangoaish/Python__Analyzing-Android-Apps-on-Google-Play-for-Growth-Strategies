# Analyzing Android Apps on Google Play for Growth Strategies

The ubiquity of mobile apps has led to a surge in their development, presenting both opportunities and challenges for app creators. In this project, we conduct a comprehensive analysis of the Android app market by scrutinizing over ten thousand apps available on Google Play across various categories. Our goal is to extract actionable insights from the data to devise strategies aimed at enhancing growth and retention in the competitive app ecosystem.

## Data Overview:

We explore two primary datasets:

- apps.csv: This file contains detailed information about the applications on Google Play, encompassing 13 features that describe each app.
- user_reviews.csv: Here, we find 100 reviews for each app, sorted by helpfulness, with text pre-processed and attributed with sentiment labels (Positive, Negative, or Neutral), polarity, and subjectivity.


## Key Tasks:

1. ### Data Cleaning:

- One of the main challenges we encounter is data cleaning, as the datasets may contain inconsistencies, missing values, or special characters in numerical columns like Installs and Price.
- We address these issues by standardizing the format of numerical columns, removing special characters, and handling missing data appropriately.

2. ### Correcting Data Types:

- We observe that certain columns, such as Installs and Price, are categorized as object data types due to mixed input types (e.g., digits and special characters).
- To facilitate analysis, we convert these columns into numeric types, ensuring they contain only numerical values.

3. ### Exploring App Categories:

- We delve into app categories to discern market trends and answer questions such as category dominance and the prevalence of different app types.

4. ### App Ratings Distribution:
- Analyzing app ratings across categories to understand overall performance and user sentiment.

5. ### App Size and Price Analysis:

- Examining the relationship between app size, price, and user ratings to inform strategies regarding app pricing and sizing.

6. ### Relation between App Category and Price:

- Delving into pricing strategies across different app categories, identifying trends and outliers to optimize pricing decisions.

7. ### Filtering Out "Junk" Apps:

- Identifying and filtering out irrelevant or malicious apps to refine our analysis and visualization.

8. ### Popularity of Paid vs. Free Apps:

- Comparing the popularity and installation rates of paid and free apps to understand user preferences and behavior.

9. ### Sentiment Analysis of User Reviews:

- Conducting sentiment analysis on user reviews to gauge user perception and satisfaction levels with paid and free apps.


## Conclusion:

Through this analysis of the Google Play Store ecosystem, we aim to derive insights that can guide app development and marketing strategies. By understanding market trends, user preferences, and sentiment, we equip ourselves with valuable information to make informed decisions in the dynamic landscape of mobile app development. However, it's essential to acknowledge the challenges and limitations inherent in the data, including data cleaning complexities and potential biases in user reviews. Nonetheless, by overcoming these challenges and leveraging the insights gained, we can drive growth and innovation in the Android app market.
