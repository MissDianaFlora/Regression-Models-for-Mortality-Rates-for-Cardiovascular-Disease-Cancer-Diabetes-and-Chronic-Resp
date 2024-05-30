# EXECUTIVE SUMMARY

This project is about predicting the Mortality Rates for Cardiovascular Disease, Cancer, Diabetes, and Chronic Respiratory Diseases in the Population of Ireland using supervised Regression Models.

The Dataset
The dataset is Mortality rate attributed to cardiovascular disease, cancer, diabetes, or chronic respiratory disease Dataset- (G0315) from the government of Ireland data website data.gov.ie

The CRISPM DM was employed to make sense of the Data. The steps included:-
I. Business Understanding
II. Data Understanding
III. Data Preparation
IV. Modeling
V. Evaluation
VI. Deployment

I. Business Understanding
This involved understanding the objectives and requirements of the project. The objectives were:-
- To determine among the four diseases which had the highest mortality rate
- To determine which year had the highest mortality rate
- To determine the area of residence with the highest mortality rate
- To predict the mortality rate for the year 2016 and compare with the actual mortality rates
  
II. Data Understanding
- collect initial data: The data was obtained from data.gov.ie, and it was loaded into Python for analysis.
- Describe data: The data was examined and the surface properties were documented e.g. data format, number of records, and number of variables.
- Explore data: Dig deeper into the data. Query it, visualize it, and identify relationships among the data.
- Verify data quality: How clean/dirty is the data? Document any quality issues
  
III. Data Preparation
It had five tasks:
- Select data: variables that were not used were dropped
Clean data: this involved:-
a) Handling Missing Data
b) Handling Duplicates if any
c) Encoding categorical variables
d)Drop the irrelevant row called state
e)Dropping some area of residence(Border, Midland, West, Dublin, Mid-East, Mid-West, South-East, South-West)
f) Handling outliers
Construct data: Derive new attributes that will be helpful. For example, derive someone’s body mass index from height and weight fields.
Integrate data: Create new data sets by combining data from multiple sources.
Format data: Re-format data as necessary. For example, you might convert string values that store numbers to numeric values so that you can perform mathematical operations.

IV. Modeling
Select modeling techniques: The algorithms were:-
KNN
Decision tree regression (CART)
Random forest
Linear regression (multiple)
Lasso regression
Ridge regression
Support Vector regression
Gaussian Naive Bayes

Build model: build the models above
Encoding the categorical Variables
Creating the features and dependent variable objects
Standardizing the data
splitting the data into training and Test set.
build various ML models
test the model on a test data set

Assess model: 
Evaluate the model performance
Maximize the model performance
Hyperparameter tuning

V. Evaluation
This phase has three tasks:
Evaluate results: Do the models meet the business success criteria? Which one(s) should we approve for the business?
Review process: Review the work accomplished. Was anything overlooked? Were all steps properly executed? Summarize findings and correct anything if needed.
Determine next steps: Based on the previous three tasks, determine whether to proceed to deployment, iterate further, or initiate new projects

VI. Deployment
 This final phase has four tasks:

Plan deployment: Develop and document a plan for deploying the model
Plan monitoring and maintenance: Develop a thorough monitoring and maintenance plan to avoid issues during the operational phase (or post-project phase) of a model
Produce final report: The project team documents a summary of the project which might include a final presentation of data mining results.
Review project: Conduct a project retrospective about what went well, what could have been better, and how to improve in the future.

