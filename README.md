# E-commerce Customer Purchase Intentions

## Repository Contents

- `notebooks`: folder containing draft notebooks with modeling process
    - `d_tree_model.ipynb`: draft notebook for decision tree and random forest model iteration
    - `log_reg_model.ipynb`: draft notebook for logistic regression model iterations
- `visualizations`: folder containing all visualzations generated in `eda_notebook.ipynb`
- `.ipynb_checkpoints`: folder containing Jupyter Notebook checkpoints, can disregard
- `eda_notebook.ipynb`: notebook with exploratory data analysis (EDA) process
- `business_insights`: notebook with final visualizations that answer the business problems
- `final_model_notebook.ipynb`: notebook with modeling process for final model that recieved the highest evaluation metric
- `online_shoppers_intention.csv`: .csv file with original research data from UCI
- `model_data.csv`: .csv file with data cleaned in `eda_notebook.ipynb`
- `READ.md`: markdown file to display README on repository

## Overview

The `online_shoppers_intention.csv` includes 12,330 sessions of online traffic to an unknown website over the period of a year. The column 'Revnue' contains a True or False value that displays whether or not a website viewer purchases the product. This serves as the target variable for the clasification problem. Using the other columns provided, we can create a classification model that can predict whether a site visitor will purhase the product.

The scoring metric will be _ _ because ____.

## Primary Business Problem

How can the company increase purchase rate among customers who visit the website?

## Business Questions

1. How does the number of visitors differ each month?
2. Do returning visitors have a higher revenue than one-time visitors?
3. What feature has the best and worst impact on revenue?

## Data & Methods

This project uses the [Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset#) from the UCI Machine Learning Repository.

The research study gathered data from each session of website traffic over the 1-year period. The 'Revenue' column was used as the target variable in this classification project. Below is a description of each column in the original dataset.

| Column Name | Description |
|-|-|
| **Administrative** | Administrative Page Value |
| **Administrative_Duration** | Duration in Administrative Page |
| **Informational** | Informational Page Value |
| **Informational_Duration** | Duration in Informational Page |
| **ProductRelated** | Product Related Page Value |
| **ProductRelated_Duration** | Duration in Product Related Page |
| **BounceRates** | Visitors who enter the site from that page and leave without visiting any other pages. |
| **ExitRates** | Calculated with all page views before exiting the website. |
| **PageValues** | Average value for a web page that a user visited before completeing an e-commerce transaction. |
| **SpecialDay** | Promximity to site visit to specific special day (e.g. Mother's Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction. |
| **Month** | Month of the year |
| **OperatingSystems** | Operating system used |
| **Browser** | Internet browser used |
| **Region** | Region of the user |
| **TrafficType** | Traffic Type |
| **VisitorType** | Returning visitor or not |
| **Weekend** | Weekend or not |
| **Revenue** | Whether revenue was generated or not, as True or False |

## Results
Insert results of EDA for business problem

## Conclusions
Might not need this section?

## Final Model Performance
Briefly discuss process for final model, and the evaluation metrics

## Next Steps
Business related next steps