# Zomato-Restaurant-Clustering-and-Sentiment-Analysis

## Introduction
Zomato, founded by Deepinder Goyal and Pankaj Chaddah in 2008, is a leading Indian restaurant aggregator and food delivery startup. It offers detailed information, menus, and user reviews for restaurants, along with food delivery services in select cities. 

This project analyzes Zomato restaurant data across various Indian cities to extract meaningful insights about the Indian food industry. It combines clustering of restaurants with sentiment analysis of customer reviews to provide useful conclusions, enhanced by comprehensive visualizations.

---

## Problem Statement
The goal of this project is to:

- Analyze customer sentiments from restaurant reviews.
- Cluster restaurants into meaningful segments based on cost, ratings, cuisines, and other features.
- Help customers discover the best dining options in their locality.
- Assist Zomato in identifying areas for service and operational improvements.
- Perform cost vs. benefit analysis based on cuisine and pricing data.

---

## Dataset Description

### 1. Zomato Restaurant Metadata
- **Name:** Restaurant name.
- **Links:** URL links of the restaurant pages.
- **Cost:** Estimated cost per person.
- **Collection:** Zomato category tags.
- **Cuisines:** Types of cuisines served.
- **Timings:** Restaurant operating hours.

### 2. Zomato Restaurant Reviews
- **Restaurant:** Name of the restaurant.
- **Reviewer:** Reviewer’s name.
- **Review:** Text of the review.
- **Rating:** Rating given by the reviewer.
- **MetaData:** Reviewer's metadata (number of reviews and followers).
- **Time:** Date and time of the review.
- **Pictures:** Number of pictures posted with the review.

---

## Project Architecture

![Project Architecture](https://github.com/Kaushik-Puttaswamy/Zomato-Restaurant-Clustering-and-Sentiment-Analysis/blob/dev/Project%20Architecture.png)

---

## Notebook Breakdown

1. **Business Problem Analysis**  
   Understand the problem and define project objectives.

2. **Data Collection**  
   Gather and combine metadata and reviews datasets.

3. **Data Cleaning and Preprocessing**  
   Handle missing values, data types, and merge datasets.

4. **Feature Engineering**  
   Create new features to improve model insights.

5. **Exploratory Data Analysis (EDA)**  
   Visualize data patterns and trends.

6. **Best Restaurants in the City**  
   Identify top-rated restaurants by city.

7. **Most Popular Cuisines in Hyderabad**  
   Analyze cuisine preferences and trends.

8. **Restaurants and their Costs**  
   Explore cost distribution among restaurants.

9. **Cost-Benefit Analysis**  
   Evaluate dining cost against customer ratings.

10. **Hypotheses Generation for Clustering**  
    Formulate hypotheses based on visual data analysis.

11. **K-Means Clustering on Cost and Ratings**  
    Segment restaurants using K-Means based on cost and ratings.

12. **Multi-Dimensional K-Means Clustering**  
    Cluster restaurants using multiple features.

13. **Principal Component Analysis (PCA)**  
    Reduce dimensionality for improved clustering.

14. **Silhouette Score**  
    Evaluate clustering quality.

15. **Cluster Exploration**  
    Interpret characteristics of each cluster.

16. **Sentiment Analysis: EDA**  
    Analyze sentiment distribution in reviews.

17. **Critics in the Industry**  
    Identify influential reviewers using metadata.

18. **Text Pre-Processing and Visualization**  
    Clean review texts and visualize sentiments.

19. **Modeling**  
    Build and evaluate sentiment analysis models.

---

## Key Findings and Conclusion

- Identification of top-rated restaurants and popular cuisines across cities.
- Insightful cost-benefit analysis for different dining options.
- Effective clustering of restaurants into distinct segments based on ratings, costs, and features.
- Comprehensive sentiment analysis revealing customer satisfaction levels and potential improvements.

---

## Future Work

- Refine clustering using advanced machine learning techniques.
- Incorporate additional features such as location data and demographics.
- Continuously update and evaluate models with new data for sustained accuracy.

---

## How to Use

1. Clone the repository.
2. Install required dependencies from `requirements.txt`.
3. Run the Jupyter notebooks in order to reproduce the analysis and visualizations.
4. Explore clustering results and sentiment analysis models.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn
- NLTK, TextBlob
- WordCloud

---

## Contact

For any questions or suggestions, please reach out at:  
**Kaushik Puttaswamy** – [LinkedIn](https://www.linkedin.com/in/kaushik-puttaswamy-data-analyst/)

---

*This project is a data science exploration and analysis of Zomato restaurant data, aiming to provide actionable insights into the Indian food industry.*




