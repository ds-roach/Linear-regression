# Linear-regression

Linear Regression
Linear Regression is Supervised Learning algorithm
Linear Regression is Regression problem

What is Linear Regression?
	Linear Regression is an algorithm that used for finding or to model the relationship between one independent variable and one dependent variable.
	
Type of Linear Regression:
	§ Multiple Regression
		Linear relationship between two or more features/independent variables with one label/dependent variable
	§ Polynomial Regression
		Modeling the relationship between one independent variable and one dependent variable using an n-th degree polynomial 
	§ Polynomial Multiple Regression
		Modeling the relationship between two or more independent variable and one dependent variable using an n-th degree polynomial 
-------------------------------------------------------------------------------------------------------------------

When should we used Linear Regression?
Some situations where linear regression may be appropriate include:
	1. Predicting a continuous value: Linear regression can be used to predict a continuous value such as the price of a house or the number of units sold.
	2. Exploring the relationship between variables: Linear regression can be used to explore the relationship between variables and understand the relative importance of different factors in explaining the dependent variable.
	3. Simple and interpretable model: Linear regression provides a simple and interpretable model, which can be useful for understanding the underlying relationships in the data.
	4. Small or moderate size dataset: Linear regression is not the best option for large and complex datasets, it is more suitable for small or moderate size datasets.
	5. The independent variables are numerical and correlated with the dependent variable: Linear regression is based on the assumption that the independent variables are numerical and correlated with the dependent variable.
	
If the relationship is non-linear, it's better to use other algorithms such as polynomial regression or decision trees.
-------------------------------------------------------------------------------------------------------------------

What are the prerequisite of a dataset that can be modeled using Linear Regression?
In order to use linear regression to model a dataset, the following assumptions and prerequisites must be met:
	1. Linearity: The relationship between the independent and dependent variables should be linear. This means that a linear equation can be used to model the relationship.
	2. Independence: The observations in the dataset should be independent of each other. This means that the value of the dependent variable for one observation should not depend on the value of the dependent variable for any other observation.
	3. Homoscedasticity: The variance of the errors should be constant across all levels of the independent variable. This assumption is also known as homoscedasticity.
	4. Normality: The errors should be normally distributed. This assumption allows for valid inferences about the population using the sample data.
	5. No multicollinearity: The independent variables should not be highly correlated with each other. This is known as multicollinearity and can lead to unstable and difficult-to-interpret regression coefficients.
	6. No outliers: The data should not contain outliers, as they can have a disproportionate effect on the regression coefficients and make the model less robust.
	7. Sufficient observations: There should be a sufficient number of observations in the dataset to accurately estimate the regression coefficients and make valid inferences about the population.
	8. Data Preprocessing: Data should be preprocessed, such as handling missing values, scaling, or encoding categorical variables, before using in a linear regression model.
	
-------------------------------------------------------------------------------------------------------------------
Polynomial Regression
Raising the polynomial degree by 1 improve the R squared value![image](https://user-images.githubusercontent.com/126078264/220904397-a097b335-1e2f-4314-9f3b-9da6db76f752.png)

