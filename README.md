# Yelp-Recommendation-System

## Project Objective

The number of reviews dropped significantly on Yelp during Covid. As the pandemic eases, we expect users would come back on Yelp to look for good restaurants to dine in at or attractions to go to. Yelp could adjust its recommendation system to provide better suggestions and search results to retain users and pursue its mission of connecting people with great local businesses.

In this project, we focused on analyzing restaurants in Ohio state, and…
- Analyzed the Yelp dataset provided by Yelp.
- Stored our JSON raw data on Google Cloud Platform Cloud Storage.
- Utilized Google BigQuery as our data warehouse.
- Ran PySpark on Google Dataproc to clean the data and develop models.
- Trained the Alternating Least Squares model as a base recommendation model.
- Ran NLP on reviews to divide restaurants into several topics.
- Fit and trained regression models to predict how users rate restaurants and recommend the highest scored restaurants.

## Repository Structure

1. **Yelp_Business Cleaner.ipynb**: Code for dividing nested columns in business table and saving into serperate tables

2. 1) **EDA.ipynb**: Includes most EDA codes and graphs
   2) **EDA- Word Clouds Generator.ipynb**: Codeoorf generating Venn diagram word clouds
   3) **EDA- User In-State and Out-of-State Behavior Analysis.ipynb** : Codes for analysing users' review activies in different states

3. **ALS Reccomendation System.ipyn**b : Code for ALS reccomendation system

4. **NLP Topic Finder.ipynb** : Code for finding topics utilizing NLP with LDA clustering

5. **Regression Recommendation System.ipynb**: Code for traning regression models to provide recommendation

## Models

Our base model had an RSME score of 1.49 and R2 of 85.9%, and our final model had an RSME score of 0.89 and R2 of 95.2%. We are confident that we could make better suggestions to more active users with our final model. In the future, we could better optimize our model by training on more data, implementing time series analysis, and using more robust NLP models to understand our users better.

# Infrastructure Overview

<img width="1440" alt="Screenshot 2024-10-18 at 6 48 57 PM" src="https://github.com/user-attachments/assets/1575dca9-6b63-4bff-82d9-3a26cdcc7404">


 
