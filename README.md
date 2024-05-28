# HEALTH INSURANCE CROSS SELL PREDICTION

#**Problem Statement**

Insurance company that has provided Health Insurance to its customers now they need to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.
Objective is to build a model to predict whether a customer would be interested in Vehicle Insurance.

**Data Description**
This dataset has 381109 Row & 12 Columns.
This dataset holds the demographical information( Person's Gender ,age ,region code),vehicel details(Vehicle age, vehicle Damage), Policy details(Premium, sourcing channel) and Response which states whether they are intersted or not.

The Dataset used for the analysis includes the following columns:

id : Unique ID for the customer

Gender : Gender of the customer

Age : Age of the customer

Driving_License : 0 - Customer does not have DL,1 - Customer already has DL

Region_Code : Unique code for the region of the customer

Previously_Insured : 1 - Customer already has Vehicle Insurance, 0-Customer doesn't have Vehicle Insurance

Vehicle_Age : Age of the Vehicle Vehicle_Damage : 1 - Customer got his/her vehicle damaged in the past. 0 -Customer didn't get his/her vehicle damaged in the past.

Annual_Premium : The amount customer needs to pay as premium in the year

PolicySalesChannel : Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

Vintage : Number of Days, Customer has been associated with the company

Response : 1 - Customer is interested, 0 - Customer is not interested

###**Project Summary**

My Project "Health Insurance cross sell prediction" is data analysis and Machine learning project that explores dataset containing detailed information health insurance customers to build a model to predict whether customers will be interested in Vehicle Insurance provided by the company.

**Step 1: Data Cleaning and Manipulation** 

Primary task is to identify and handle any null values or inconsistent values and do all necessary data cleaning or data manipulations to ensure integrity of the data and data ready for analysis.


**Step2: Exploratory Data Analysis**

Then exploring/analysing columns to understand their relationship or patterns.

(i)Analysing the Age distribution and creating Age groups for simple analysis.

(ii)Understanding Driving License status first and then driving license status per Gender,Age Group.

(iii)Assess the proportion of Gender.

(iv)Performing analysis on Region Code variable to get total number of customers per each region and response status per each region.

(v)Vehicle Damage variable important to be analysed, hence visualizing the damage rate per each Age group of customer and Vehicle age.

(vi)Annual Premium is another important factor. Firstly understanding the distribution of Annual Premium and also identifying the outliers through boxplot. Furthermore understanding the Average Premium per Age group and Vehicle age, damage together.

(vii)Response states the interest of the customer in getting Vehicle Insurance. Trying understand the response rate given that they already had a vehicle insurance. Also visualizing the "Reponse" rate per Age Group and Gender.

(viii)Lastly analysing the Response count per each policy channel.

(ix)Finishing the EDA with a coorelation plot for numerical variables and pairplot.


**Step3: Hypothesis Testing**

Defining hypothesis statements for the dataset and performing hypothesis testing to get conclusion about my statements.

**Step4: Feature Engineering and Data Pre-processing**

Performing all necessary data pre-processing steps like handling the outliers efficiently, encoding all categorical features then selecting the best features based on feature importance. Performing the data scaling, data splitting and also handling the imbalanced data.


**Step5: Machine Learning Model Implementation**

We aim at training model with trained data using different algorithms and further perform hyper tuning to improve the results. Validating the results with test data to evaluate the model performance. And getting the best model based on evaluation metrics.





