# [Deciding Factors in League of Legends](https://github.com/charliesong66/Deciding-Factors-in-League-of-Legends/blob/master/deciding-factors-in-league-of-legends.ipynb)

### This notebooks tries to find out what are the key reasons a team wins/loses, and at the same time build a model predicting game results only using data from the first 10 mins. The data consists of SOLO QUEUE games at high ELO (DIAMOND I to MASTER)

### The algorithms used are:
* Random Forest
* Logistic Regression
* Principal Compnent Analysis (PCA)

### Summary of findings:

The two most important statistics on winning/losing are:
* Gold difference
* Experience difference



|   | feature |	eigenvalue |
| --- | --- |
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
