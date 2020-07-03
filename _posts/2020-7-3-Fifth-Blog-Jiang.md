---
layout: post
title: Fifth Blog
---

# Outline of Project 2

This project is about making a prediction on the popularity of online news and the original dataset can be found from this [website](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity).
It is made up of five main parts: introduction, data study, modeling, weekday analysis and conclusion. 

For the first part, 'Introduction', the online news data has been described; the project purpose has been proposed and the adapted methods have been discussed. 

For the second part, 'Data Study', it primarily discusses the selected variables and split 70% of the data into the training set and the rest into the test set. Also, it makes 
a summary about the response variable *shares* and the predictors. 

For the third part, 'Modeling', it is the most important part of this project and it has been divided into two types of models fit: linear regression fit and ensemble model fit.
For the linear regression fit, it considers two different linear regression fits: multiple linear regression and binary logistic regression; for the ensemble model fit, it
considers the bagged trees model and the boosted trees model respectively.

For the forth part, 'Weekday Analysis', it adapts the automation in R to create seven files from Monday to Sunday automatically. 

For the last part, 'Conclusion', it makes a general conclusion for predicting the target *shares* related to some predictors.

# Findings from Project 2

For this project, I am interested in predicting the popularity of the online news with some predictor variables. For the linear regression fit, after comparing the AIC and BIC
values, the binary logistic model is better than the multiple linear model; for the ensemble model, after comparing the accurary and the misclassification rate, the boosted tree
model is the better one. 

# Reflection on Project 2

## What would you do differently?

For this finished project, I treated the variable 'data_channel_is_*' as numeric instead of factors. If it was asked to do the project again, I would treat these variables as 
factors and consider more about the relationships between other variables and weekdays since it adapts code to cycle through seven days in the end.

## What was the most difficult part for you?

For this project, the automation part is the hardest for me. 

I did not realise that I need to create a new R script to create these seven .md files automatically and how to create these files at first. After reviewing the related notes and
codes, I finally come up with the solution.

## What are your big take-aways from this project?

I have learned how to use the parameter in Rmd and how to automatically create files through R code. 


The link for the website about my project 2: 

https://jiangyu1208.github.io/ST558-Summer20-Project-2/

[Website](https://jiangyu1208.github.io/ST558-Summer20-Project-2/).
