# Multiple-Linear-Regression

Data Description:

The dataset used is the soccer player dataset. It has information about various players from different clubs, and it provides data over ten features with a number of goals as the target variable.

Tech Stack:

Language: Python
Libraries:  numpy, pandas, statsmodel, seaborn, matplotlib, sklearn, scipy, plotply

I have applied multiple linear regression to predict Scores of soccer league Players. Firstly, I fitted model using all the variables and checked whether our model satisfies following statistical assumptions:

1. Normality of dependent variable
2. Independence of errors or Autocorrelation
3. Linearity of predicted values.
4. Homoscedasticity
5. Multicollinearity

After this, I removed some of the variables (Weight, Height, and MinutestoGoalRatio) which were redundant and not holding useful information for the data.

Lastly, I added the categorical variable Club to the dataframe using one-hot encoding and tested the model. 

The final accuracy of the model was 96.6%
