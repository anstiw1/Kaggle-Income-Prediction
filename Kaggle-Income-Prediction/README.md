# Project 4: Hackathon

#### Executive Summary

"Good, Fast, Cheap"
In this project, we are creating a model to determine if a person's income level is above or below $50,000. Our team was constrained by only being able to use a smaller size of training data, we were sample constrained.  We modeled the data using a pipeline to run 6 different classification models and the random forest classifier performed best.

---

#### Problem Statement

In this project, we are creating a model to determine if a person's income level is above or below $50,000.  Our team was constrained by only being able to use a smaller size of training data.  We modeled the data using 6 different classification model and the random forest classifier performed best.


---

#### Data Cleaning and EDA

The data was imported and then the data was cleaned and explored before analyzed.  



---

#### Data Dictionary

Sample Data Dictioary

|Feature|Type|Description|
|---|---|---|
|Age|int|Log of age of the individual| 
|education-num|int|Highest Grade finished|
|wage|boolian|Total hours worked in a week|
|finwgt|int|Log of the number of people the census believes the entry represents|
|capital-gain|int|Size of capital gain in dollars|
|native-country_united-states|boolian|country of individual is United States)|
|relationship_wife|boolian|relationship of individual is wife|
|sex_male|boolian|Sex of individual is male)|
|occupation_sales|boolian|Occupation of individualis sales|



---

#### Models

We use Logistic regression, random forest classifier, adaboost classifier, KNeighbors Clasifier, Bagging Classifier, and SVC were used to test our data.  The Random Forest Classifier performed the best with a cross val score of 86.3.


---

![ROC Curve](https://i.imgur.com/YAQmJAE.png)
