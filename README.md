# Private Health Insurance Analysis

# About Dataset:

   Insurance Dataset for Predicting Health Insurance Premiums in the US" is a collection of data on various factors that can influence medical costs and premiums
   for health insurance in the United States. The dataset includes information on 10 variables, including age, gender, body mass index (BMI), number of children,
   smoking status, region, income, education, occupation, and type of insurance plan. The dataset was created using a script that generated a million records of
   randomly sampled data points, ensuring that the data represented the population of insured individuals in the US. The dataset can be used to build and test
   machine learning models for predicting insurance premiums and exploring the relationship between different factors and medical costs.

# Data Source:

   A data set from Kaggle was used as the source of our analysis: Insurance Data for Machine Learning | Kaggle

   https://www.kaggle.com/datasets/sridharstreaks/insurance-data-for-machine-learning

# Deployment of site:

   Landing page is deployed via (https://github.com/MinaliBheda/Project_4.git)  

# The purpose of the project:

   * To develop a machine learning model for a data set containing insurance premiums based on 3 numerical and 8 categorical data
     and utilize/optimize the model to predict insurance premium cost for customers.
   * Provide data analysis on the submitted and predicted data, that provides useful information for business planning and marketing.


# Data Visualisation: Insurance_visualizations.ipynb

   For visualizations,seaborn and matplotlib libraries were used.Visualizations displays correlation between the insurance charges per customer based on their
   Age, Body Mass Index(BMI), Medical History , Occupation and Number of Children. 

![Alt text](image-1.png)

# Tableau:
   
   The webpage for Visualizations created using Tableau can be found on below link: 

   https://public.tableau.com/app/profile/irina.schultz/viz/insurance_dataset/MedicalHisRegionCharges?publish=yes

# Machine Learning: insurance_machine_learning.ipynb 

   The data set file has list of features and target as shown below.  

   ## Features : 

    * Numerical Columns:
      * age
      * bmi(body mass index)
      * children 

    * Categorical Columns: 
      * gender 
      *	smoker 
      * region 
      * medical_history 
      * family_medical_history 
      * exercise_frequency 
      * occupation 
      * coverage_level

    * Target Columns:
      * charges 

# Models Used:

    Linear Regression
    Decision Tree Regressor

    ## Mean Squared Error and Root Mean Squared Error for Linear Regression on test data: 

    Mean Squared Error for Linear Regression for Testing Values: 83547.32738257291
    Root Mean Squared Error for Linear Regression for Testing Values: 289.04554551588046

    ## Mean Squared Error and Root Mean Squared Error for Decision Tree Regression on test data: 

    Mean Squared Error for Decision Tree Regression: 257286.54899019946
    Root Mean Squared Error for Decision Tree Regression: 507.2342151217714
    
    ## Conclusion on better model:
    
    Root Mean Squared Error measures the average difference between values predicted by a model and the actual values. It provides an estimation of how well
    the model is able to predict the target value (accuracy). The lower the value of the Root Mean Squared Error, the better the model is. 
        
    Thus,as seen above, the RMSE value for Linear Regression is lower than the Decision Tree ,It can be concluded that Linear Regression Model is the better
    model compared to Decision Tree.


![Alt text](<Screen Shot 2023-08-28 at 9.31.49 pm.png>)

![Alt text](<Screen Shot 2023-08-28 at 9.32.04 pm.png>)


# Conclusion:

    A Machine Learning model offers swift and precise predictions for specific scenarios. In our scenario, it succesfully generated insurance premiums charges
    based on Customer's Age,Gender,Occupation,BMI,Medical History ,No of Children etc.

