# Project Overview: Predict House Price in Delhi NCR with Machine Learning
This project has a purpose to create machine learning model that can predict the house price in New Delhi.

# <b> Requirement for running the code </b>
Library needed to be installed: <br>
- Data analysis and visualization: numpy, pandas, matplotlib, pyplot <br>
- Machine Learning modelling: sklearn

# <b> 1. Business Understanding </b>
## Background Problems
For the people that want to buy the house, sometimes it is difficult to identify whether the house price is normal or overvalued. The bunch of features (bedroom, bathroom, location, etc) in each house could make it more difficult to compare the prices between the house
## Purpose
With this machine learning model, comparing the prices between the houses will be easier and more automated 

# <b> 2. Data Understanding and Preparation </b>
- Data Understanding
  - Check the column name to see whether the column is important or not
  - Check data type
  - Check value of every column to see whether the value is make sense or not
- Data Cleansing
  - Removing the column that not related
  - Drop missing value
- Feature Engineering
- Outlier removal
  - Outlier removal with business logic
  - Outlier removal with mean and standar deviation
- One Hot Encoding for categorical column

# <b> 3. Machine Learning Modelling </b>
- Separate label and feature
- Split training and testing data
- Use K-Fold cross validation to find the split combination with the best accuracy
- Use Grid Search CV to find the model with the best accuracy 


