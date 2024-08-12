
# Assessing Regression Model Performance in Predicting Shoe Size

 ### Project Overview
 ---

This project investigates a dataset containing individuals' height, weight, gender, and shoe size. The main goal is to assess if the dataset's features (height, weight, and gender) are adequate for accurately predicting shoe size. Additionally, the project aims to evaluate the performance of a regression model applied to this dataset, assessing its potential for developing a reliable predictive model based on feature selection.
The evaluation metrics used to measure the model's effectiveness include:

 * 1. Mean Squared Error (MSE)
 
 * 2. Mean Absolute Error (MAE)
 
 * 3. R² Score

### Data Sources
---

The primary dataset for this analysis is sourced from [Kaggle.com](https://www.kaggle.com/datasets/peimandaii/dataset-of-people) and includes information about people's height, weight, and shoe size dataset.

### Project Tools 
---

- **Language:** Python - Data Cleaning, Analysis, Feature Selection, Reports. 
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit Learn

  #### Exploratory Data Analysis (EDA)
    
  I conducted an exploratory data analysis to investigate the relationships between numerical features and the target:

  1. Investigating the relationship between Height and Shoe Size
     
![alt text](https://github.com/dgeorge1010/Shoe-Size-Prediction/blob/65a50cad933a2ca778f7f0d1117532f3652757f4/download1.png) 

The scatterplot illustrates the relationship between height (in centimeters) and shoe size. The data points follow a roughly straight-line path from the lower left to the upper right. It shows a positive linear relationship between the two variables, meaning as height increases, shoe size tends to increase as well. However, some points do not fit well within the general trend. This means that such outliers can influence the slope and intercept of the regression line, especially if they are not representative of the population.



  


