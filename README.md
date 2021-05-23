# Starbucks Capstone Project - Offer Recommendation

## Motivation

This project is a capstone project of Machine Learning Engineer Nanodegree program of Udacity. In this project, I will develop a solution to appropriately recommend promotional offers to Starbucks customers who are under their reward program. Following aspects are covered in this project-

1. Data Cleaning: Ingesting the data in to dataframes and conducting missing data analysis, transformation etc.
2. Data Exloration: Explore the data by slicing and dicing the data sets to understand the distribution of the available data
3. Model Development: Develop the appropriate model depending on the distribution of the data. In this project, a recommendation engine is developed using Funk SVD algorithm
4. Evaluate the model: Using metrics like Precision@k, Recall@k and F1 Score@k, evaluate the model

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

Python: 3.9.1

Packages: math, json, pandas, numpy, collections, matplotlib.pyplot, seaborn, calendar, chart_studio, plotly, sklearn


### Installing

You can install python from this [link](https://www.python.org/downloads/release/python-391/).

Packages can be installed using the 'requirements.txt' that is available in the repository.

```python
pip install -r requirements.txt
```

### Files used:
The analysis is present in the jupyter notebook - 'Starbucks_Capstone_notebook.ipynb'. This takes input of 3 files-

* profile.json:- Data set containing the list of customers who are members of rewards program. This data set contains user specific details such as gender, age, income and age of membership
* portfolio.json:- Data set contains details about the offers. It contains information like the reward of the offer, channels through which the offers are presented, conditions to use the offer, duration of the offer, and type of the offer
* transcript.json:- This data set contains the activity details of the customers of Starbucks who are enrolled in to rewards program. The data set contains the details such as amount of the transaction, type of offer used, duration of the offer use before expiry, and reward obtained for the offer


### Summary

Funk SVD model is a powerful recommendation engine model that is based on collaborative filtering methodology. This means, that it is a powerful and a great tool to recommend offers to an existing customer base. If the customer already exists in the system, and has had a decent history, then this methodology works very well. The model fails when it comes to predict for a new customer. This is a limitation of the model developed and must be used keeping that in mind. Otherwise, the model throws light on each customer’s probable behavior towards the offers that were not offered in the past. This helps the marketing department to make an informed decision about targeting right set of customers for their campaigns.

## Licensing, Authors, Acknowledgements

The data was made available by Starbucks and it is a simulated data of their customers belonging to the rewards program. I have to acknowledge Stackoverflow community as they rescued me from the errors and bugs faced during the analysis.

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/Senrique/mle_capstone/blob/main/LICENSE) file for details

Please feel free to use my code for your purposes.
