# Amazon Product Reviews Sentiment Analysis

## Project Overview

This project performs Sentiment Analysis and Customer Review Analytics on the Amazon Product Reviews dataset containing over 568,000 customer reviews. The objective is to analyze customer opinions, identify sentiment patterns, and extract meaningful insights from review text using Natural Language Processing (NLP) techniques.

The project combines Exploratory Data Analysis (EDA), sentiment classification, word frequency analysis, word clouds, and TextBlob-based sentiment analysis to understand customer behavior and product perception.

---

## Dataset Information

* Dataset: Amazon Product Reviews Dataset
* Total Records: 568,454 Reviews
* Features:

  * ProductId
  * UserId
  * ProfileName
  * HelpfulnessNumerator
  * HelpfulnessDenominator
  * Score
  * Summary
  * Text
  * Time

---

## Objectives

* Analyze customer review sentiments.
* Classify reviews into Positive, Negative, and Neutral categories.
* Explore rating patterns and review behavior.
* Identify commonly used words in positive and negative reviews.
* Compare rating-based sentiment with NLP-based sentiment.
* Generate business insights from customer feedback.

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* NLTK
* WordCloud
* TextBlob
* Jupyter Notebook

---

## Methodology

### 1. Data Cleaning

* Checked missing values.
* Removed duplicate records.
* Removed unnecessary columns.
* Created a Review_Length feature.

### 2. Exploratory Data Analysis

* Rating Distribution Analysis
* Review Length Distribution
* Average Review Length by Rating
* Customer Feedback Patterns

### 3. Rating-Based Sentiment Analysis

Reviews were classified as:

* Positive: Ratings 4 and 5
* Neutral: Rating 3
* Negative: Ratings 1 and 2

### 4. NLP Analysis

* Text preprocessing
* Stopword removal
* Word frequency analysis
* Positive and Negative word clouds

### 5. TextBlob Sentiment Analysis

* Generated polarity scores from review text.
* Classified reviews based on polarity values.
* Compared NLP-based sentiment with customer ratings.

---

## Key Findings

### Customer Sentiment Distribution

* Positive Reviews: 78.1%
* Negative Reviews: 14.4%
* Neutral Reviews: 7.5%

### Review Length Analysis

* Average review length varied across rating categories.
* Three-star reviews were the longest on average.
* Five-star reviews were generally shorter and more concise.

### Word Frequency Analysis

Common positive words included:

* good
* great
* love
* best

Common negative words included:

* bad
* buy
* tried
* box

### NLP Insights

* TextBlob sentiment analysis aligned strongly with highly positive reviews.
* Some low-rated reviews contained positive words, leading to sentiment mismatches.
* This demonstrates the limitations of lexicon-based sentiment analysis and the importance of contextual understanding.

---

## Visualizations

The project includes:

* Rating Distribution
* Review Length Distribution
* Average Review Length by Rating
* Sentiment Distribution
* Positive Word Cloud
* Negative Word Cloud
* Top Positive Words
* Top Negative Words
* Rating vs NLP Sentiment Comparison

---

## Business Recommendations

* Continue maintaining product quality to sustain customer satisfaction.
* Monitor negative reviews to identify recurring issues.
* Analyze detailed three-star reviews for improvement opportunities.
* Consider advanced NLP models for more accurate sentiment detection.

---

## Conclusion

This project analyzed over 568,000 Amazon customer reviews using data analytics and sentiment analysis techniques. The analysis revealed a strong positive sentiment among customers and highlighted differences between rating-based and NLP-based sentiment classification. The findings provide valuable insights into customer behavior, review patterns, and product perception.

---

## Author

Janwi Kumari

