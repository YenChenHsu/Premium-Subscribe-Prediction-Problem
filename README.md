# Introduction
XYZ Music Company offers two business models: "Freemium" and "Premium." To enhance the efficiency of the marketing campaign, we aim to predict which Freemium users are most likely to upgrade to Premium. This targeted approach is intended to optimize resource allocation and maximize conversion rates.

# Data Set
This data set contains 41,540 records with 25 features, including 1540 adopters and 40,000 non-adopters.  

# Solution Map
<img width="889" alt="solution map" src="https://github.com/YenChenHsu/Premium-Subscribe-Prediction-Problem/assets/57134574/1141c44c-1b55-47dc-a773-d118e77966f4">

# Technical Document Guide
To optimize our predictive model, we conduct feature selection to enhance our model performance. 
Among 25 attributions, we utilized different techniques to conduct feature selection for the classification model, including Random Forest, Cosine Similarity, and Information Gain Filter. 
We obtained top 5 features, including 'songsListened', 'delta_avg_friend_age','delta_songsListened', 'avg_friend_age', 'lovedTracks'. Model AUC performance improved from around 50% to 76%. 

# Result Report
Our business report can be found in the executive summary pdf, in conclusion, with our predictive model (decision tree), the customer conversion rate increases by 116% after model implementation, and the total marketing cost can be reduced by 53%. 

# Contributor
Yen Chen Hsu, Tiffany Chen, Thomas Farrell, Ameya Rahurkar, Avanindra Singh
