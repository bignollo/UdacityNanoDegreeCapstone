## StarBucks Capstone Project ##

[Blog Post](https://bignollo.com/2022/11/29/udacity-capstone-project-starbucks-project/)

This repo was created to store all the files for the Udacity DataScience NanoDegree.
the following files are part of the project:
* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed
* Starbucks_Capstone_notebook - The Jupyner Notebook with all steps 

### Python Libraries ###

Below libraries were used in this project.

* pandas
* numpy
* datetime
* seaborn
* Sklearn model selection
* SkLearn Logisctic regresion, RandomFores and AdaBoost
* SkLearn Preprocessing and data split

### Motivation ###

The motivation behind the project is to understand the profiles of the consumer and which of those profiles are more likely to react to the different offers.
for that the following are the base questions:
* How does my population looks like.
* What profile is more likely to complete an offer.
* What are the offers that draws more attention

### Evaluation Metric ###

f1-score will be used as an evaluation metric to assess models performance.

### Results ###
The results for the projects are two-fold:
1. An exploratory analysis - this analysis suggest that there is a clear target group that will respond as expected to the offers, this means once they view the offer they will fullfill the confiditions
  - In this area there is still space for improvements with more in depth analysis and if more data can be used to better understand, for instance the impact of informational.
  - Also with access to data in real team offers can be made more personalized in order to target groups of customes more accuarate.
2. Model creation - After a lot of data cleaning, Dataset where in shape for test multiple models: Randonforest, Logistic Regresion and AdaBoost, the last one did not move forward due to low results.
  - Logistic regression performed a decent job( __0.8726 F1__ ) and improve almost nothing after applying the optimal parameters provided by Grid Search ( __0.8789 F1__)
  - Randon Forest performed better on initial run ( __0.9352 F1__ ) and improved slightly after Grid Search ( __0.9359 F1__ ), this model was the best performer
Random Forest model was cross validated with a __94.7%__ Accuracy and 0.003 standard deviation

### Acknowledgements ###
Data provided by Starbucks and the environment for developemtn from Udacity. Also a big thanks to all instructors and reviewers for the great material

more details can be found on the following [Blog Post](https://bignollo.com/2022/11/29/udacity-capstone-project-starbucks-project/). 
