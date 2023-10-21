# U.S.-Medical-Insurance-Costs-Analysis

Loading Libraries: The code starts by importing various Python libraries, including NumPy, SciPy, Matplotlib, Seaborn, Pandas, Statsmodels, and others, to perform data analysis and statistical modeling.

Loading Data: It loads the insurance dataset from a CSV file into a Pandas DataFrame named 'df'.

Exploratory Analysis: This section involves initial data exploration:

Summary statistics of the dataset are printed using the describe() method.
The first few rows of the dataset are displayed with head().
The average age of the patients is calculated and displayed.
A bar chart is created to show the number of people in each region.
The average insurance charges per region are calculated and displayed.
A histogram is created to visualize the distribution of insurance charges based on smoking status.
Correlation Analysis: In this section, the code examines the correlation between variables:

A correlation matrix is calculated and printed.
Scatter plots are created to visualize the relationship between age, BMI, and children with insurance charges.
The impact of smoking on insurance costs is visualized using scatter plots.
A correlation matrix is calculated specifically for smokers.
Linear Regression Modeling: Linear regression is performed to model the relationship between independent variables (age, BMI, and children) and the dependent variable (charges). This includes:

Creating a linear regression model using Statsmodels.
Checking assumptions of linearity, homoscedasticity, and normality.
Calculating the Variance Inflation Factor (VIF) to check for multicollinearity.
Statistical Testing: The code performs statistical tests and provides interpretations:

It calculates and prints the F-statistic and associated p-value to determine the overall significance of the model.
It computes the t-statistic and p-value for the 'children' variable to test its individual significance.
3D Scatter Plot: A 3D scatter plot is created to visualize the relationship between age, children, and charges.

Refining the Model: A new linear regression model is created with the retained predictors (age and children). This model is displayed with a summary.

Prediction: The new model is used to make predictions for insurance charges based on given predictor values (age and children).

Confidence and Prediction Intervals: Confidence and prediction intervals are extracted for the regression model's parameters (X1 and X2) with a significance level of 0.05, and the intervals are printed.

In summary, this code conducts exploratory analysis, regression modeling, statistical testing, and visualization to understand the factors affecting medical insurance costs in the dataset. It also includes checks for assumptions and provides interpretation of the statistical results.
