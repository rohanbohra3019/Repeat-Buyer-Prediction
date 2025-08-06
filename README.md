# Repeat Buyer Prediction
## Project Overview
This project focuses on leveraging data from promotional shopping events on an e-commerce platform. The primary objectives are:
- Predicting the probability that new buyers will repurchase from the same merchants within six months.
- Reducing promotional costs.
- Identifying one-time buyers to increase Return on Investment (ROI).
## Need for Repeat Buyer Prediction Model
In the evolving e-commerce landscape, understanding customer needs, loyalty, and behavior is crucial. Despite having extensive customer activity data
- Businesses struggle to convert this data into actionable insights for promotional sales or loyalty programs.
- A significant number of customers remain single-time buyers.
- Identifying loyal customers for targeted promotions is essential for maximizing profits.
## Exploratory Data Analysis (EDA)
Our data analysis included:

- Gender distribution across age groups, highlighting predominant age groups.
- Correlation plots for statistical analysis.
- Sales patterns analysis during promotional days and their correlation with brands, users, and items.
- Popularity trends of items among users.
- Gender-based activity categorization using pie charts.
## Feature Engineering
We processed the dataset to engineer 153 features based on user-merchant interactions, categorized as:

- Time-related features.
- Count features.
- Action count features.
- Ratio of actions features.
- Monthly and Double 11 Day features.
## Feature Ranking
To determine the most effective features, we employed:

- Regression Model.
- SHAP analysis.
- Random Forest Regressor.
- The Random Forest approach yielded the most promising features for our final prediction model.

## Models Comparison and Accuracy
We tested various models, with the following accuracy rates:

- Bayes Classifier: 63% Accuracy.
- Random Forest: 89% Accuracy.
- Convolutional Neural Network (CNN): 73% Accuracy.
- Recurrent Neural Network (RNN): 84% Accuracy.
## Insights
Key findings include:

- Loyalty doesn't always correlate with interest in special events or promotions.
- The Click-merchant ratio and merchant-specific browsing are strong loyalty indicators.
- Merchants with a limited brand selection tend to retain more loyal customers.
## Conclusion
Our comprehensive analysis utilizing various machine learning and neural network models concluded that the Random Forest model outperformed others with an accuracy of 89%. This suggests that the Random Forest approach is most suitable for predicting loyal or repeat buyers in this context.

## References
Repeat Buyer Prediction for E-commerce 
- https://dl.acm.org/doi/10.1145/2939672.2939674. 
- https://www.researchgate.net/publication/305998405_Repeat_Buyer_Prediction_for_E-Commerce
