
# Diamond Price Modelling
In this notebook, we will explore the factors that affect the price of a diamond with a goal of finding a model to help predict the price of diamonds.

## Motivation
In order to build an end-to-end regression (i.e., evaluation) project in Python, based on the prices, I chose the diamonds price dataset that was sourced from seaborn (a Python data visualization library). This dataset contains the prices and other attributes of almost 54,000 diamonds. It is a great dataset to work with Python programming, data analysis and visualizations, data science and machine learning.

## Installation

You have to download some required Libraries to run the project.

```bash
  pip install pandas
```
 ```bash
  pip install numpy
```   
 ```bash
  pip install seaborn
``` 

## Features
Steps necessary for the success of the project:
- Data Understanding : One of the biggest parts of data science is, handling data. A well-managed set of data sources and collection of data marks the difference between a successful project and a confusing mess,it is also important to keep track of the quality of the data in order to ensure that unclean data doesn’t hamper the results. Moreover, there should be a back-and-forth with the business understanding step for a truly flexible approach.


- Data Preparation : Data preparation is the step where data to be used is determined,data mining goals must be solidified, along with data cleaning and integration processes.
1- Missing values or outliers :
- The dataset doesn’t include any missing values but diamonds with z equal to 0 or greater than 10, y equal to 0 or greater than 10 and x equal to 0 are outliers.
2- Dummy variables for categorical variables :
- The dataset includes 3 categorical variables (cut, color, and clarity). I chose to create dummy variables for those categorical variables using a “replace” function.

- Modeling: 
1- This is where most of the work is done, with the modeling method being integral to the kind of problem to be solved. If the wrong method is used, the results obtained will not be comparable to results gained when the method is right.

2- A test model must also be designed for proof-of-concept and suitability tests. The model should also be fitted for the problem, with testing and backpropagation being important parts if the model used is a neural network.

3- The approach must also be tailored with respect to the goals and the business and data understanding in order to create a good fit for the problem. In this manner, the model should be assessed.