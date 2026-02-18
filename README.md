# Basketball-Analysis
This research uses basketball raw and precalculated derived data obtained from Kaggle (which are accumulated from nba) in order to explore the relationship between different predictors and dependent variable. Explicitly there are 3 variables that are important to win a basketball game which through this research will be analyzed by modeling them.
1.	Predicting the win or loss based on various numerical and categorial variable.
2.	Explore Assist Rate and possession
3.	Analyze Points Scored based on rebounds and steals
Proposed data and analysis plan:
1.	We’ll visualize various raw data using pair correlation, scatterplot and histogram.
2.	Out of 119 variables, we would use 15 to 20 variables to perform the regression analysis and build linear models out of them using stepwise and/or best subset regression
3.	Perform Model usability and hypothesis test of all the beta coefficients
4.	Interaction among variables like steal, rebound, assist to turnover, steal to turnover
5.	Test if multiplication (log) model can give better results in some models
6.	Perform Nested F-Test since there are so many independent variable
7.	PRESS Model Validation Test
8.	Check multicollinearity using VIF
9.	Perform tests of Residual and Outliers tests
Data Description:
No of observations: 44284, No of columns: 44, # of predictors: 15 to 20 based on model used,
Response: Points scored by team, Assist rate for team, Steal to turnover ratio for team
Source of the data: 
Title: NBA Enhanced Box Score and Standings (2012 - 2018),  File: 2012-18_officialBoxScore.csv
Link: https://www.kaggle.com/datasets/pablote/nba-enhanced-stats?select=2012-18_officialBoxScore.csv

