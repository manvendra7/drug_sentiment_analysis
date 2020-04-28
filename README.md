# Drug Sentiment Analysis

### Problem Statement

This is a typical NLP task where we have to predict the sentiment of the users from their reviews.

### Data Description
[Data Source](https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29)

The dataset provides patient reviews on specific drugs along with related conditions and a 10 star patient rating reflecting overall patient satisfaction.

**Attribute Information:**

1. drugName (categorical): name of drug
2. condition (categorical): name of condition
3. review (text): patient review
4. rating (numerical): 10 star patient rating
5. date (date): date of review entry
6. usefulCount (numerical): number of users who found review useful

### Exploratory Data Analysis

Through our EDA we were able to find some interesting facts about our data. Below are the things that we found 
* The most top condition were pain, birth control and high blood pressure.
* Most the conditions have multiple drugs.
* A single drug can be used for multiple conditions.
* The number of reviews has increased in last 3 years.
* As the ratings has increased average yearly rating has decresed.
* Ratings of the users are extreme. They only rate when they find the drug very effective or the drug shows some side effects.
