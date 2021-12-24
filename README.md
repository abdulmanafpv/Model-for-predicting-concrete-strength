
# Model for predicting concrete strength

# About

The actual concrete compressive strength (MPa) for a given mixture under a specific age 
(days) was determined from laboratory. Data is in raw form (not scaled). The data has 8 
quantitative input variables, and 1 quantitative output variable, and 1030 instances
(observations). 
#  Context:
Concrete is the most important material in civil engineering. The concrete compressive 
strength is a highly nonlinear function of age and ingredients. These ingredients include 
cement, blast furnace slag, fly ash, water, superplasticizer, coarse aggregate, and fine 
aggregate. 

Attribute Information: 
in kg in a m3 mixture 

Fly ash Cement : measured in kg in a m3 mixture 

Blast : measured: measured in kg in a m3 mixture 

Water : measured in kg in a m3 mixture 

Superplasticizer : measured in kg in a m3 mixture 

Coarse Aggregate : measured in kg in a m3 mixture 

Fine Aggregate : measured in kg in a m3 mixture 

Age : day (1~365) 

Concrete compressive strength measured in MPa
# Objective: 
Modeling of strength of high performance concrete using Machine Learning 
# Steps and tasks:
1. Deliverable -1 (Exploratory data quality report reflecting the following) 

a. Univariate analysis 

i. Univariate analysis – data types and description of the independent 
attributes which should include (name, meaning, range of values observed, 
central values (mean and median), standard deviation and quartiles, analysis 
of the body of distributions / tails, missing values, outliers 

b. Multivariate analysis 

i. Bi-variate analysis between the predictor variables and between the 
predictor variables and target column. Comment on your findings in terms of 
their relationship and degree of relation if any. Presence of leverage points. 
Visualize the analysis using boxplots and pair plots, histograms or density 
curves. Select the most appropriate attributes 

c. Pick one strategy to address the presence outliers and missing values and perform 
necessary imputation 

2. Deliverable -2 (Feature Engineering techniques) 

a. Identify opportunities (if any) to create a composite feature, drop a feature etc. 

b. Decide on complexity of the model, should it be simple linear model in terms of 
parameters or would a quadratic or higher degree help 

c. Explore for gaussians. If data is likely to be a mix of gaussians, explore individual 
clusters and present your findings in terms of the independent attributes and their 
suitability to predict strength 

3. Deliverable -3 (create the model ) 

a. Obtain feature importance for the individual features and present your findings 

4. Deliverable -4 (Tuning the model) 

a. Algorithms that you think will be suitable for this project 

b. Techniques employed to squeeze that extra performance out of the model without 
making it overfit or underfit 

# Contents
This is a Concrete Data set. This Data set contain 1030 rows and 9 columns.

* For predicting concrete strength, I developed and compared various models.

For Creating a model i Used
1) Linear Regression.
2) Random Forest Regression
3) Bagging Regression
4) Elastic Net Regression
5) SVM(Support Vector Machine)
 
# Result:
From these models Random Forest Regression model gives highest score when compared to other models(0.9117909557650435).

# Tools Used

1) Python
2) Pandas
3) Scikit-learn
4) Matplotlib
5) Jupyter Notebook


# Technologies Used
![Scikit_learn_logo_small](https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg)

If you liked what you saw, want to have a chat with me about the portfolio, work opportunities or collabration, shoot an email at pvmanaf02@gmail.com
