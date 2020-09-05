# Contact
### charlie.song66@gmail.com
<br>
<br>

# [Deciding Factors in League of Legends](https://github.com/charliesong66/Deciding-Factors-in-League-of-Legends/blob/master/deciding-factors-in-league-of-legends.ipynb)

[Link to this project on Kaggle](https://www.kaggle.com/yuankunsong/deciding-factors-in-league-of-legends)

## In this project I tried to find out what are the key reasons a team wins/loses, and at the same time build a model predicting game results only using data from the first 10 mins. The data consists of SOLO QUEUE games at high ELO (DIAMOND I to MASTER)

### The algorithms used are:
* Random Forest
* Logistic Regression
* Principal Compnent Analysis (PCA)

### Summary of findings:

The two most important statistics on winning/losing are:
* Gold difference
* Experience difference

### Key features given by Random Forest:
![alt text](https://raw.githubusercontent.com/charliesong66/charlie-portfolio/master/images/lol%20factor1.png?raw=true)

### Key features given by the first component in PCA:

|   | feature |	eigenvalue |
| --- | --- | --- |
|15 |	blueGoldDiff | 	0.277441 |
|34	| redGoldDiff	| 0.277441 |
|35	| redExperienceDiff	| 0.266243 |
|16	| blueExperienceDiff	| 0.266243 |
|18	| blueGoldPerMin	| 0.226717 |
|10	| blueTotalGold	| 0.226717 |
|29	| redTotalGold	| 0.223054 |
|37	| redGoldPerMin	| 0.223054 |
|12	| blueTotalExperience	| 0.213231 |
|31	| redTotalExperience	| 0.212999 |

<br>
<br>

# [Credit Card Default - Analysis and Prediction](https://github.com/charliesong66/Predicting-Credit-Card-Default-Using-XGBoost/blob/master/predicting-credit-card-default-using-xgboost.ipynb)
[Link to this project on Kaggle](https://www.kaggle.com/yuankunsong/predicting-credit-card-default-auc-0-793)

## This project aims to analyze credit card default rates. The dataset is from information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

### The method used was XGBoost, with extensive hyperparameter tuning.

### Key findings: the most important factors affecting credit card repayment in a given month are:
* Statement amount in previous month
* Repayment status in previous month
* Amount of payment in previous month

### Feature importance given by the XGBoost Model:
![alt text](https://github.com/charliesong66/Charlie_Song_DataScience_Portfolio/blob/master/images/creditcard1.png?raw=true)

### Building a model using all data but the current month, then validate the model by making prediction on that month acheived an AUC of 0.793. Below is the confusion matrix:
![alt text](https://github.com/charliesong66/Charlie_Song_DataScience_Portfolio/blob/master/images/creditcard2.png?raw=true)

<br>
<br>

# [COVID-19 Visualisation and Analysis](https://www.kaggle.com/yuankunsong/covid-19-visualisation-analysis)

## I have made some visualisation on COVID-19 data, this includes views by Countries, by Continents, daily increases, daily new cases etc. The second part of this project has more in depth exploration on the situation in the U.S. by different states.

### Some of the plots are below:

{% include covid11.html %}
{% include covid22.html %}
{% include covid33.html %}
{% include covid44.html %}
{% include covid55.html %}
