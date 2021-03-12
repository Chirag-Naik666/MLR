# MLR
## Multiple linear regression model predicting the life expectancy using life expectancy dataset.

### About the project-
   In this project I am using linear regression to predict the life expectancy using the features in the dataset. 

### Python Packages used- Pandas,Numpy,Scipy,sklearn,statmodels,Seaborn and matplotlib.
      
### About the data set (life_expectancy) :-
   The data-set related to life expectancy, health factors for 193 countries has been collected from the same WHO data repository website and its corresponding economic data was collected from United Nation website. Among all categories of health-related factors only those critical factors were chosen which are more representative.

### Acknowledgements-
The data was collected from WHO and United Nations website with the help of Deeksha Russell and Duan Wang.

### The project involves-
1) **Null value treatment-**
   Treating the null values using median or forward fill based on data description.
  
2) **Exploratory data analysis-**
   Univariate and Bivariate analysis using KDE plot, boxplots and heatmap.

3) **Feature transformation-**
   Using sklearn preprocessing standard scalar to scale the numeric values.

4) **Building Linear Regression model using assumptions-**
   Various tests like durbin-watson,vif,goldfeld quandt is used to check for the 5 assumptions.

5) **Model performance evaluation-**
   Model rmse, mean absolute error, R-square and adjusted R-squared are used to evaluate the final model.
  
### Conclusion- 
   The model predicts the life expectancy with the adjusted r-squared accuracy of 96.1%.
