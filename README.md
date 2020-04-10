
# Ames Housing Data and Kaggle Challenge


**Objectives & Background**

The main objective is to create regression model(s) based on the Ames Housing Dataset. This model will predict the price of a house at sale. The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It includes over 70 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. The Ames Housing is an increadible alternative for data scientists looking for a revamped version of the frequently used Boston Housing dataset.
The Ames Housing dataset is used in the Advanced Regression Techniques challenge on the Kaggle website: https://www.kaggle.com/c/dsi-us-10-project-2-regression-challenge. 

### Process included:<br>
- Data Cleaning & EDA<br>
- Preprocessing and Modeling:<br>
    >MLR<br> 
    >LASSO<br>
    > RIDGE<br>
  

**Conclusion and Recommendations (rooted from MLR model)**:

Comparing to the other models, MLR model showed a better result. 

As of now **`85.3%`** of variance in the sale price can be explained by this model,in other words, model can generalize from train/test data to predict the house value, with **`+/-$27K`** price error. This model is built using numeric datasets, and can be improved by leveraging feature engineerign to include interesting features like Neighborhood house style and materials. 
This model can be used for the following purposes:

#### - Predicting Property Price
This model can be used for any dataset that includes similar attributes on house features to predict the property's selling price.

#### - Inference
This model can be used to outline and test some of the most important factors/features that influence house's value.
