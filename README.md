
# Evaluating Regression Model Performance in Predicting Shoe Size

 ### Project Overview
 ---

This project investigates a dataset containing individuals' height, weight, gender, and shoe size. The main goal is to assess if the dataset's features (height, weight, and gender) are adequate for accurately predicting shoe size. Additionally, the project aims to evaluate the performance of a regression model applied to this dataset, evaluating its potential for developing a reliable predictive model based on feature selection.
The evaluation metrics used to measure the model's effectiveness include:

1. Mean Squared Error (MSE)
 
2. Mean Absolute Error (MAE)
 
3. R² Score

### Data Sources
---

The primary dataset for this analysis is sourced from [Kaggle.com](https://www.kaggle.com/datasets/peimandaii/dataset-of-people) and includes information about people's height, weight, and shoe size dataset.

### Project Tools 
---

- **Language:** Python - Data Cleaning, Analysis, Feature Selection, Reports. 
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit Learn

  #### Exploratory Data Analysis (EDA)
    
  I conducted an exploratory data analysis to investigate the relationships between the numerical features and the target:

####  1. Investigating the relationship between Height and Shoe Size
     
![alt text](https://github.com/dgeorge1010/Shoe-Size-Prediction/blob/65a50cad933a2ca778f7f0d1117532f3652757f4/download1.png) 

#### Interpretation

The scatterplot illustrates the relationship between height (in centimeters) and shoe size. The data points follow a roughly straight-line path from the lower left to the upper right. It shows a positive linear relationship between the two variables, meaning as height increases, shoe size tends to increase as well. However, some points do not fit well within the general trend. This means that such outliers can influence the slope and intercept of the regression line, especially if they are not representative of the population.


#### 2. Investigating the relationship between Weight and Shoe Size
     
![alt text](https://github.com/dgeorge1010/Shoe-Size-Prediction/blob/eb1dd0141779ef98a331ad5f79608cb898247492/download2.png)

### Interpretation

The scatterplot shows the relationship between weight (in kilograms) and shoe size. It displays a positive linear relationship, indicating that as weight increases, shoe size tends to increase. While there is a positive linear relationship between weight and shoe size, the variability and spread suggest that weight alone may not be a perfect predictor of shoe size. The relationship might be influenced by other factors, or a more complex model might be needed to make accurate predictions across all weight ranges.


### Interpretation of the evaluation metric results

1. The Mean Absolute Error (MAE) measures the average magnitude of errors in a prediction set, regardless of their direction. It is computed by averaging the absolute differences between predicted and actual values. An MAE of 1.361 means that, on average, the model's predictions deviate from the actual values by approximately 1.361 units.¶
2. The Mean Squared Error (MSE) is calculated by averaging the squared differences between predicted and actual values. By squaring the errors, MSE gives more weight to larger discrepancies, making it more sensitive to significant errors compared to MAE. An MSE of 3.757 indicates a relatively higher variance in the errors.
3. The RMSE, which is the square root of the MSE, serves as an error metric expressed in the same units as the target variable, thus enhancing its interpretability compared to MSE. For instance, an RMSE of 1.938 signifies that the average prediction error is approximately 1.938 units
4. The Root Mean Squared Error (RMSE), which is the square root of the MSE, provides an error metric in the same units as the target variable, improving interpretability. For example, an RMSE of 1.938 signifies that the average prediction error is approximately 1.938 units.


### Recommendations

1. You can consider improving the model by adding more features to better capture the relationships and trying out more advanced models like polynomial regression, decision trees, or ensemble models to improve performance.
2. You can conduct an error analysis to investigate large errors particularly to understand where the model fails including addressing data issues. Also, it is important to examine error patterns to further refine the preprocessing of data and model.
3. You must enhance data quality ensuring data is clean and representative of the population and if possible, include data volume to improve model learning and generalization.
4. Use cross-validation to ensure metrics are robust across different sets.
5. You can consider applying model calibration such as applying techniques like Lasso or Ridge regression to prevent overfitting and you can also apply hyperparameter tuning to find the best model configuration.


