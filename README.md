# Aygaz-Machine-Learning-Bootcamp
This repository contains my project for this bootcamp.I tried to apply some algorithms to a fake job report dataset.

You can find this dataset here:https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction

I have used random forest,logistic regression and k-means algorithm to analyze this data.

My accuracy scores were 97 percent in random forest and 96 percent in logreg.

If you want to give this a look on kaggle here's the link:https://www.kaggle.com/code/beyzacankurtaran/beyza-cankurtaran-aygaz-machine-learning-bootcamp

My silhoutte score for k-means were 52 percent(its bad i know)

This dataset contains these columns:
job_id
title
location
department
salary_range
company_profile
description
requirements
benefits
telecommunicating
has_company_logo
has_questions
employment_type
required_experience
required_education
industry
function
fradulent

Since this dataset columns were having text columns i have to do some vectorization(TF-IDF vectorization to be specific) to 
convert text data into numerical format suitable for machine learning models.

Other than that i used some EDA and plots.You can review other details on the notebook.

If you have any kind of questions you can reach me at byzcnkrtrn@gmail.com
