# Linear-regression

Linear Regression
Linear Regression is Supervised Learning algorithm
Linear Regression is Regression problem

What is Linear Regression?
	Linear Regression is an algorithm that used for finding or to model the relationship between one independent variable and one dependent variable.
	
Type of Linear Regression:
- Multiple Regression
	Linear relationship between two or more features/independent variables with one label/dependent variable
- Polynomial Regression
	Modeling the relationship between one independent variable and one dependent variable using an n-th degree polynomial 
- Polynomial Multiple Regression
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
Raising the polynomial degree by 1 improve the R squared value

Understanding Bias and Variance
The inability for machine learning to capture the true relationship between variables and the outcome is known as Bias

High Bias
![image](https://user-images.githubusercontent.com/126078264/220911424-8f9ee7a3-6d29-40ef-bc45-a1718f394a26.png)

When its has a high bias, when it comes to applying unseen observations, it gives a pretty good estimate

Low Bias
![image](https://user-images.githubusercontent.com/126078264/220911521-76bffac8-93b1-4b77-ad48-3342cc3c86fb.png)


The Residual Sum of Squares which is the sum of error in prediction, 
in graph below the straight line is pretty low compared to the curvy line

RSS on Straight Line
![image](https://user-images.githubusercontent.com/126078264/220911558-ce08c2e9-762f-44eb-941b-e37113255417.png)


RSS on Curvy Line 
![image](https://user-images.githubusercontent.com/126078264/220911690-ff48680f-8c78-4e05-809a-f2e4a1a9657d.png)


Variance = the fit between the dataset 
The Curvy Line has a High Variance and the RSS is different for different dataset
The Straight Line has Low Variance and the RSS is similar for different dataset

High Bias, with the line hugging as many as possible
Low Variance, with the line resulting in consistent prediction using different datasets
![image](https://user-images.githubusercontent.com/126078264/220911732-d505f28e-6a78-40aa-97a7-a98421ec4595.png)

-------------------------------------------------------------------------------------------------------------------

To strike a balance between finding a simple model and a complex model, you can use technique such as:
- Regularization is a technique that automatically penalizes the extra features you used in your modeling
- Bagging, is a type of ML that use ensemble learning to evolve ML models. Bagging uses a subset of the data and each sample trains a weaker learner. The Weaker Learner can then be combined (through averaging or max vote) to create a strong learner that can make accurate predictions.
- Boosting, similar to Bagging, except that it uses all of the data to trains each learner, but the data points that misclassified by previous learners are given more weight so that subsequent learners will give more focus to them during training.
