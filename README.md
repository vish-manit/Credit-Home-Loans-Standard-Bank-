# Credit-Home-Loans-Standard-Bank-

Task
Credit / Home Loans - AutoML vs Bespoke ML
Standard Bank is embracing the digital transformation wave and intends to use new and exciting technologies to give their customers a complete set of services from the convenience of their mobile devices. As Africa’s biggest lender by assets, the bank aims to improve the current process in which potential borrowers apply for a home loan. The current process involves loan officers having to manually process home loan applications. This process takes 2 to 3 days to process upon which the applicant will receive communication on whether or not they have been granted the loan for the requested amount. To improve the process Standard Bank wants to make use of machine learning to assess the credit worthiness of an applicant by implementing a model that will predict if the potential borrower will default on his/her loan or not, and do this such that the applicant receives a response immediately after completing their application.

You will be required to follow the data science lifecycle to fulfill the objective. The data science lifecycle (https://www.datascience-pm.com/crisp-dm-2/) includes:

Business Understanding
Data Understanding
Data Preparation
Modelling
Evaluation
Deployment.
You now know the CRoss Industry Standard Process for Data Mining (CRISP-DM), have an idea of the business needs and objectivess, and understand the data. Next is the tedious task of preparing the data for modeling, modeling and evaluating the model. Luckily, just like EDA the first of the two phases can be automated. But also, just like EDA this is not always best.

In this task you will be get a taste of AutoML and Bespoke ML. In the notebook we make use of the library auto-sklearn/autosklearn (https://www.automl.org/automl/auto-sklearn/) for AutoML and sklearn for ML. We will use train one machine for the traditional approach and you will be required to change this model to any of the models that exist in sklearn. The model we will train will be a Logistic Regression. Parts of the data preparation will be omitted for you to do, but we will provide hints to lead you in the right direction.

The data provided can be found in the Resources folder as well as (https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset).

train will serve as the historical dataset that the model will be trained on and,
test will serve as unseen data we will predict on, i.e. new ('future') applicants.
Part One
There are many AutoEDA Python libraries out there which include:

dtale (https://dtale.readthedocs.io/en/latest/)
pandas profiling (https://pandas-profiling.ydata.ai/docs/master/index.html)
autoviz (https://readthedocs.org/projects/autoviz/)
sweetviz (https://pypi.org/project/sweetviz/)
and many more. In this task we will use Sweetviz.. You may be required to use bespoke EDA methods.

The Home Loans Department manager wants to know the following:

An overview of the data. (HINT: Provide the number of records, fields and their data types. Do for both).

What data quality issues exist in both train and test? (HINT: Comment any missing values and duplicates)

How do the the loan statuses compare? i.e. what is the distrubition of each?

How many of the loan applicants have dependents based on the historical dataset?

How do the incomes of those who are employed compare to those who are self employed based on the historical dataset?

Are applicants with a credit history more likely to default than those who do not have one?

Is there a correlation between the applicant's income and the loan amount they applied for?

Part Two
Run the AutoML section and then fill in code for the traditional ML section for the the omitted cells.

Please note that the notebook you submit must include the analysis you did in Task 2.
