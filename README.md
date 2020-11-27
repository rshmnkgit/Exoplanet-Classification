# Exoplanet Exploration
#### Classifying exoplanets using Machine learning classification models
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

## Objective
Create machine learning models capable of classifying candidate exoplanets from the raw dataset.

## Model Performance Evaluation
### Logistic Regression Model
The model is 98% accurate in predicting the false positive cases, but it is not a good option in predicting the candidate and confirmed categories, which are only about 65% accurate. So this model is not a perfect model for this dataset. 

### K-Nearest Neighbors (KNN) Model
The KNN model prediction is similar to the logisitc regression model. This is 98% accurate in predicting the false positive category

### Gaussian Naive Bayes Model
This model is only 44% accurate in predicting the candidate category. So this is not a good model for the dataset.

### Support Vector Machine (SVM) Model
This SVM model prediction is better than both logisitc regression, gaussian naive bayes and knn models. This is 98% accurate in predicting the 'False positive' category, 81% accurate in 'Candidate' category and 79% accurate in predicting 'Confirmed' category



