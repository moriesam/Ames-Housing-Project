
# Ames Housing Data and Kaggle Challenge


**Objectives & Background**

Objectives & Background

As a data scientist my task here is to create a regression model based on the Ames Housing Dataset. This model will predict the price of a house at sale. The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It includes over 70 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. The Ames Housing is an increadible alternative for data scientists looking for a revamped version of the frequently used Boston Housing dataset.
The Ames Housing dataset is used in the Advanced Regression Techniques challenge on the Kaggle website: https://www.kaggle.com/c/dsi-us-10-project-2-regression-challenge. My school, General Assembly is hosting a competition on Kaggle for the same topic which provides me an opportunity as a DSI student to use the platform for practicing advanced predictive modeling process and then refine models over time.

Requirements

Problem Statement & Data Analysis Plan
Data Cleaning & EDA
Preprocessing and Modeling - 3 models are provided: 
    >MLR 
    >LASSO 
    > RIDGE
  
Conclusion and Recommendations

**Conclusion and Recommendations (rooted from MLR model)**:

Comparing to the other models, MLR model showed a better result. 

As of now **`85.3%`** of variance in the sale price can be explained by this model, indicating that the model is just right. In other words, model can generalize from train/test data to predict the house value, with **`+/-$27K`** price error. This model is built using numeric datasets, and can be improved by leveraging feature engineerign to include few key features like Neighborhood by leveraincluding some key features like Neighborgood, style and materials. Nevertheless, this model can be used for the following purposes:

<>Prediction<>
This model can be used for any dataset that includes similar attributes on house features to predict the property's selling price.

<>Inference<>
This model can be used to outline and test some of the most important factors/features that influence house's value.

<>Optimize for accuracy<>
This model can be imporved by leveraging feature engineering to include  interesting features like Neighborhood house style and materials. 
