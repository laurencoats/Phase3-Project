# Coupon Usage Classification

## Presentation and Analysis/Analytics by Lauren Coats

## Problem

ABC family of companies is looking to out a new product they tested it in some locations and though its a great product people are not buying it. ABC family of companies want to put out coupons for the product to generate buzz behind the product but they only want to send coupons customers who are likely to use the coupon. 

## Data

Data is provided by [Kaggel]( https://www.kaggle.com/vasudeva009/predicting-coupon-redemption) and the [Tanzanian Ministry of Water](http://maji.go.tz/) originally as part of a competition hosted by [DrivenData](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/).

It contains approximately over 78,000 instances.
## Methodology
* Exploratory Data Analysis of the dataset to understand each data feature among each other and to the labels.

* Clean the data and impute data for the significant amount of missing data in the dataset.  Columns high missing value percent where dropped. Columns such as married created a new value unknown.  

* The dataset is highly imbalanced, oversampling will be needed to create synthetic data to balance the clases.

* Implement Supervised Learning Classifiers. Five classifiers were implemented and the best performing had its hyperparameters tuned.  Random Forest was the best performing and the others were Logistic Regression with SMOTE oversampling, and Decision Tree with SMOTE oversampling.

## Model Performance
Performance was judged on overall F1-score and balanced recall.
For this data accuracy was not important because even with the model day no customers used coupons it would be right 99.1% of the time. 
Because of the extreme imbalance and limited amount of information the training set had a hard time fitting to any model. Which resulted in poor performance with the test set. 


## Recommendations
•	Send coupons to customers in the top 2 age brackets. 

## Future Work
* **Find out why repeat coupon users used coupons:**
* **Separate coupons used my type:**
* **See if there are other similarities between people who use coupons:**  such as other hobbies, amount of free time, weather they work or not, ect


