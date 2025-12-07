# CodeAlpha_DataAnalytics_Task
“Amazon Fine Food Reviews – EDA, Visualization &amp; Sentiment Analysis”

# Amazon Fine Food Reviews – EDA, Visualization & Sentiment Analysis

This project is created as part of the CodeAlpha Data Analytics Internship.

## Objective
- Perform Exploratory Data Analysis (EDA)
- Visualize rating trends and review patterns
- Perform Sentiment Analysis on review text using TextBlob

## Dataset
- Amazon Fine Food Reviews dataset (568,454 reviews, 10 columns)
- Columns: Id, ProductId, UserId, ProfileName, HelpfulnessNumerator, HelpfulnessDenominator, Score, Time, Summary, Text

## Steps Performed
1. Data loading and cleaning
2. Exploratory Data Analysis (shape, info, describe, null values)
3. Feature engineering: converting Time to Year
4. Visualizations:
   - Distribution of ratings
   - Number of reviews per year
   - Average rating per year
5. Sentiment Analysis:
   - Polarity calculation using TextBlob
   - Labeling reviews as negative, neutral, positive
   - Sentiment distribution and comparison with ratings

## Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- TextBlob

## Conclusion
- Most reviews have ratings of 4 and 5, indicating overall positive satisfaction.
- Number of reviews increases over the years.
- Sentiment analysis shows majority positive sentiment, matching the rating distribution.


