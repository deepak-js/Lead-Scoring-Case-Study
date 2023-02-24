# X Education Lead Scoring Case Study

## Table of Contents

- [Problem Statement](#Problem_Statement)
- [Goals](#Goals_of_the_Case_Study)
- [Expected Results](#Results_Expected)
- [Data Extraction](#Data_Extraction)
- [Process](#Process)
- [Contribution](#Contribution)

## Problem_Statement

An education company named X Education sells online courses to industry professionals. The company wishes to identify the most potential leads, also known as ‘Hot Leads’, to increase their lead conversion rate. The task is to build a model that assigns a lead score to each of the leads such that the customers with a higher lead score have a higher conversion chance, and the customers with a lower lead score have a lower conversion chance. The target lead conversion rate is around 80%.


The dataset provided consists of around 9000 leads with various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. The target variable is the 'Converted' column, which tells whether a past lead was converted or not.

## Goals_of_the_Case_Study

The goals of this case study are:

- Build a logistic regression model to assign a lead score to each of the leads.
- Handle additional problems presented by the company which the model should be able to adjust to.
- Create a well-commented Jupyter notebook, a Word document with solutions to all the problems, a presentation, and a summary report.

## Results_Expected

The expected deliverables for this case study are:

- A well-commented Jupyter notebook with at least the logistic regression model, the conversion predictions and evaluation metrics.
- A Word document filled with solutions to all the problems.
- A presentation to present the analysis to the chief data scientist of the company.
- A summary report in PDF format explaining how the assignment was proceeded and the learnings gathered.

## Data_Extraction

The source file was given as a zip file. It inclued 3 files in it.

* Assignment Subjective Questions
* Leads Data Dictionary
* Leads

    **Assigned Subjective Questions** contains these following 4 questions.
    1.	Which are the top three variables in your model which contribute most towards the probability of a lead getting converted?

    2.	What are the top 3 categorical/dummy variables in the model which should be focused the most on in order to increase the probability of lead conversion?

    3.	X Education has a period of 2 months every year during which they hire some interns. The sales team, in particular, has around 10 interns allotted to them. So during this phase, they wish to make the lead conversion more aggressive. So they want almost all of the potential leads (i.e. the customers who have been predicted as 1 by the model) to be converted and hence, want to make phone calls to as much of such people as possible. Suggest a good strategy they should employ at this stage.

    4.	Similarly, at times, the company reaches its target for a quarter before the deadline. During this time, the company wants the sales team to focus on some new work as well. So during this time, the company’s aim is to not make phone calls unless it’s extremely necessary, i.e. they want to minimize the rate of useless phone calls. Suggest a strategy they should employ at this stage.

**Leads Data Dictionary** contains the description of every column name and where as __Leads.csv__ contains the data which to be analyzed.

## Process
The data were analyzed using python with the help of __Jupyter Notebook__. Multiple packages imported and by following process the model building taken place.

1. Importing Necessary packages
2. Loading & Reading the Data
3. Understanding the Data
4. Data Cleansing
5. Exploratory Data analysis
6. Train / Test split
7. Model building
8. Model evaluation

## Contribution

### Partner 1

- Name: Manish Dabhade
- Email: manishdabhade08@hotmail.com

### Partner 2

- Name: Dharan R
- Email: ramdharan1998@gmail.com

### Partner 3

- Name: Deepak Raja S
- Email: deepakselvam27@gmail.com


