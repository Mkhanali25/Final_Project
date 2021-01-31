# Final_Project

## Overview

[Link to Presentation Slides](https://docs.google.com/presentation/d/1xdDUYNJqjwQh7HjSNzms4qzsJXtMZ27hIY0XhTGuiYQ/edit#slide=id.p)

### Files

### **Selected topic**

Our selected topic was Election results, COVID, and Demographic Data by Counties.

Reasons the topic was selected:
* Current Event 
* The dataset we selected was fairly easy to navigate
* There were many topics to conduct our analysis 
* Our dataset was fairly large with enough columns and values to complete an analysis.

### **Description of the source of data**

Our data is in a CSV file from from kaggle
[Data Link](https://www.kaggle.com/etsc9287/2020-general-election-polls?select=county_statistics.csv)

![ERD](Resources/QuickDBD_Draft.png)

### **Questions the team hopes to answer with the data**

* Is there a correlation between COVID cases and voter turnout?
* Is there a relationship between income and voter affiliation?
* How much changed between the 2016 election and the 2020 election?

## Data exploration phase

When exploring our dataset we had a fairly large amount of columns and rows. Based off the data we selected certain columns to further research. We have broken these columns into the following categories:

    1. Counties
    2. Election 2016 Results
    3. Election 2020 Results
    4. COVID
    5. County Wealth Distributions 
    6. County Demographics 
    7. County Gender Distribution  

## Analysis phase of the project

### Tableau

- [Link to 2016-2017 Election Analysis Storyboard on Tableau Pubic](https://public.tableau.com/profile/carolina4264#!/vizhome/2016-2020ElectionAnalysis/2016and2020ElectionResultsAnalysis)

### **Technologies, languages, tools, and algorithms used**

    - Considered technologies: SQLite, Jupyter Notebook, Flask App, SQLAlchemy
    - Technologies used:
      - PostGres & SQLite
      - Jupyter Notebook & Python 
      - QuickDBD
      - Tableau
      - Amazon Web Services 


## Machine Learning Model
After cleaning our dataset we will be conducting an logistic regression model for our data. We want to build a model that will predict how different demographics and factors have affected the way people voted in the 2020 election. We also want to see if these demographics and factors have any correlation with the number of covid cases in those areas and if that, in turn, had any correlation with the way that people voted in that area. 

Why Logistic Regression? 
* This is the best fit Machine Learning Model for our data
* Supervised Machine Learning→ classification
* Answers the question of “who did people vote for in both elections?”
* Explains the relationship between one dependant binary variable and multiple independent variables
* Target → who won each state
* Features → Votes per candidate, Covid data, Demographics data, wealth data


## Result of analysis
![2016 confusion matrix](https://github.com/Mkhanali25/Final_Project/blob/main/Images/2016_confusion.png)
![2020 confusion matrix](https://github.com/Mkhanali25/Final_Project/blob/main/Images/2020_confusion.png)
![Biden Clusters](https://github.com/Mkhanali25/Final_Project/blob/main/Images/Biden_cluster.png)
![Trump Clusters](https://github.com/Mkhanali25/Final_Project/blob/main/Images/Trump_cluster.png)




**Recommendation for future analysis**

**Anything the team would have done differently**

## ROLES

* Square- Muhammad
* Triangle- Andreea
* Circle- Mylissa
* X- Phil
