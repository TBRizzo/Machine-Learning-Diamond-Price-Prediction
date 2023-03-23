<h1 align="center"><img src="https://bit.ly/2VnXWr2" width="60">

<h1 align="center">Machine Learning: Diamond Price Prediction with Linear Regression </h1>

<p align="center"> Fourth project developed in the Ironhack Data Analysis Bootcamp </h1>

![image](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
![image](https://img.shields.io/badge/pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![image](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=NumPy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![image](https://img.shields.io/badge/Seaborn-lightblue.svg?style=for-the-badge&logo=Seaborn&logoColor=blue)
![image](https://img.shields.io/badge/scikitlearn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

##  💻 About the project</br>

The main objective of this project was to estimate the price of Rick’s (from Pawn Stars) 5000 diamonds (rick_diamonds.csv) achieving the smallest amount of error, so they can sell it properly.

The metric of success was, of course, money. Specifically, the goal was to obtain a root mean squared error below 900 dollars.

To achieve the goal, we were provided with a base dataset (diamonds.csv), with the historical price of other diamonds and their characteristics. We cleaned the data, performed an EDA and built the linear regression model using scikit-learn.

## 🛠 Data Gathering:

As mentioned before, the data was obtained through webscrapping from the raider.io page, from all main seasons that have already ended, creating a csv file with "role" (tank, healer or dps), "season", "class" and "region".
In this repositorie, you can also find the raider.io's public API notebook. The problem with the public API is that the number of pages from which data can be extracted is 100, which greatly limited the amount of data and was therefore not considered.

## 🛠 Data Cleaning/EDA:

Some of the data was a bit messy so some adjustments were needed to clean it up. So the first step was to clean up the data.

After that, EDA showed the relationship between price and variables, where we could see that the best candidates to be considered in the model were "carat", "cut" and "color".

##  💻 Result Analysis:

Using different models (each csv 'version' is the result of a model), it was possible to achiev a RMSE of 791.55 in v5.
