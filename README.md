# Covid-19-Tweets-Sentiment-Analysis-capston_project_3
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

Multi-class Classification Project 

![final project image](https://github.com/RAm-SaGar-863/Covid-19-Tweets-Sentiment-Analysis-capston_project_3/assets/128234583/39be5823-5af3-441d-86cc-b54a522855d7)

## Introduction
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

The CoVid-19 pandemic has been an unprecedented global crisis that has impacted lives and livelihoods worldwide. The outbreak led to lockdown measures, forcing people to stay indoors and significantly altering daily routines and interactions. Social media platforms, particularly Twitter, emerged as a prominent medium for individuals to express their thoughts and emotions during these challenging times. This analysis focuses on gauging the sentiments of individuals by analyzing their tweets on Twitter to understand the prevailing emotions and opinions during the pandemic.

## Approach
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### Text Preprocessing
---
The analysis began with preprocessing the tweet data to clean and prepare it for analysis. Text normalization techniques such as removing special characters, converting text to lowercase, and lemmatization were applied to standardize the text data.

### Exploratory Data Analysis (EDA)
---
An exploratory analysis of the preprocessed tweets was conducted to gain insights into the overall sentiment distribution and identify patterns or trends in the data. This step allowed us to understand the key themes and emotions prevalent among Twitter users during the pandemic.

### Feature Engineering & Pre-Processing
---
Relevant features were extracted from the tweets to prepare them for modeling. Techniques like Count Vectorization and TF-IDF Vectorization were employed to convert the text data into numerical form, making it suitable for machine learning algorithms.

### Model Training
---
Various machine learning algorithms were employed to classify the tweets based on sentiments. The algorithms used included:

1. Logistic Regression with Grid Search CV: A popular algorithm for binary classification, Grid Search CV was used to optimize hyperparameters for better model performance.

2. Decision Tree Classifier: A tree-like model that makes decisions based on feature values. Both Count Vectorization and TF-IDF Vectorization techniques were applied.

3. K-Nearest Neighbors (KNN): A non-parametric algorithm that classifies data based on its neighbors. Count Vectorization and TF-IDF Vectorization were used to transform the data.

4. Support Vector Machine (SVM) Classifier: A powerful algorithm for binary classification. Both Count Vectorization and TF-IDF Vectorization were applied to the text data.

5. Random Forest: An ensemble method combining multiple decision trees. Count Vectorization and TF-IDF Vectorization were used to represent the text data.

6. Stochastic Gradient Descent: This optimization algorithm was applied for training various models using Count Vectorization and TF-IDF Vectorization techniques.

## Conclusion
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

The Twitter sentiment analysis during the CoVid-19 pandemic provided valuable insights into the prevailing sentiments and emotions of individuals during these challenging times. By leveraging Twitter data and employing various machine learning algorithms and vectorization techniques, we gained a deeper understanding of the sentiments expressed by people, helping us comprehend the impact of the pandemic on society. This analysis contributes to understanding the prevailing public sentiments during crises and can aid in making informed decisions for future similar situations.


