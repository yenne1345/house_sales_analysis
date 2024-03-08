# House Sales Analysis Project - MATH/DA 220-01

**Authors:** Yen Nguyen, Hoa Nguyen, Minh Le  
**Date:** 12/17/2023

## Overview

Welcome to House Sales Analysis Project! This collaborative project was conducted by a group of 3 members as part of the Applied Statistics course (MATH/DA 220). The project aims to analyze house sale prices in King County between May 2014 and May 2015, leveraging statistical analyses, data visualization, and various regression techniques.

## Contents

### I. Describing Data

1. **Introduction**
   - King County, Washington, is a vibrant and populous region known for its innovation and rich cultural tapestry. As part of our project, we leverage a Kaggle dataset encompassing house sale prices in King County from May 2014 to May 2015. Through statistical analyses and data visualizations, we aim to decipher the impact of various factors on property values, contributing to a nuanced understanding of the real estate landscape in King County.

2. **Ethical Consideration**
   - Our work underscores the importance of prioritizing privacy and confidentiality when handling this dataset. With details about homes, we emphasize anonymization to protect individual identities. We adhere to informed consent principles, legal regulations, and transparency in data collection, promoting ethical standards. Addressing biases in pricing practices, our approach enhances the accuracy and significance of house price analysis.

3. **Data Exploration**
   - Our dataset, covering homes sold in King County during the specified timeframe, includes 21 features. For this project, we focus on key features such as price, bedrooms, bathrooms, floors, square footage, waterfront views, and more. Visualizations, including summary tables and a bar chart showing price distribution across different zip codes, provide an insightful exploration of the dataset.

4. **Statistical Analysis and Interpretation**
   - Analyze trends and relationships through boxplots of log-transformed prices by condition and view, a correlation heatmap, and scatter plots revealing connections between log-transformed prices and features like interior living space, grading points, and ground level.

### II. Inference

1. **Hypothesis Test and Confidence Interval (Waterfront Views)**
   - Assess the statistical significance of the difference in average housing prices between properties with and without waterfront views.

2. **Hypothesis Testing (Low vs. High Condition Properties)**
   - Compare the average prices of low-condition (condition = 1) and high-condition (condition = 5) houses, considering the variances.

3. **Bootstrapped Hypothesis Test (Construction Quality)**
   - Evaluate variance differences between houses with low-quality (grade < 7) and high-quality (grade >= 7) construction through bootstrapped hypothesis testing.

4. **Correlation Test (Number of Functioning Rooms)**
   - Conduct Pearson’s product-moment correlation to examine the relationship between house prices and the number of bedrooms, bathrooms, and floors.

### III. Regression

1. **Simple Linear Regression Models**
   - Examine assumptions and implement linear regression models for price and sqft_above.

2. **Multiple Regression Models**
   - Utilize pairs plots to assess assumptions and employ stepwise variable selection methods for a comprehensive multiple regression approach.

3. **Logistic Regression Models**
   - Predict high_price using logistic regression with sqft_living as the predictor, creating a new column for classification.

4. **New Technique - Random Forest**
   - Introduce the Random Forest algorithm for classification, categorizing prices into "low," "medium," or "high." Explore data preprocessing, model building, and evaluation techniques.

### IV. Limitations & Conclusions

- **Limitations:** Acknowledge the reliance on a single dataset from King County within a specific timeframe. Highlight the potential lack of generalizability to other geographical areas and time periods. Suggest future research directions, incorporating diverse datasets for a broader perspective.

- **Conclusions:** Summarize key findings, emphasizing the potential influence of location (zip codes), waterfront views, and interior features on house prices. Discuss correlations and nuances revealed by the analysis, providing valuable insights for stakeholders in the King County real estate market.

### V. Reference

- Kaggle dataset reference: [House Sales in King County, USA](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/data).
