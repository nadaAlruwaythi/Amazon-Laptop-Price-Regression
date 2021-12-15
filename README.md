# Amazon_Laptops_Price_Prediction


 # Introduction

* Amazon represents one of the largest marketplaces on the Internet. People use its services on a daily basis to order groceries, books, laptops, and even web hosting services. The aim of this project is to scrape laptop data from the amazon website then build a regression model to predict an approximate price for the laptop.


# Goals

- The model predicts the price of the laptop

# Data Description

- We will scrape data from https://www.amazon.com
- We will target the laptop data; we need to scrap at less than 1000 page
- In this project we plan to use the following as features:

| *Features* | *Data Types* |
| --- | --- |
| 1.Brand | Categorical |
| 2.Standing screen display size | Numerical |
| 3.Processor Brand | Categorical |
| 4.Processor Speed | Numerical |
| 5.Processor Count | Numerical |
| 6.RAM Size | Numerical |
| 7.Hard Drive Size | Numerical |
| 8.Hard Disk Description | Categorical |
| 9.Hard Drive Interface | Categorical |
| 10.Operating System | Categorical |
| 11.Graphics Chipset Brand | Categorical |
| 12.Item Weight | Numerical |

# Tools 

- Python
- Jupter notebook
- Beautiful soup
- Seaborn
- Pandas
- statsmodels
- sklearn
- requests
