## **Objective**

The objective of this assignment is to develop a Semantic Classification model. You will be using Word2Vec method to extract the semantic relations from the text and develop a basic understanding of how to train supervised models to categorise text based on its meaning, rather than just syntax. You will explore how this technique is used in situations where understanding textual meaning plays a critical role in making accurate and efficient decisions.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business problem that your project is trying to solve?
- What is the dataset that is being used?

## General Information

The objective of this assignment is to develop a Semantic Classification model. You will be using Word2Vec method to extract the semantic relations from the text and develop a basic understanding of how to train supervised models to categorise text based on its meaning, rather than just syntax. You will explore how this technique is used in situations where understanding textual meaning plays a critical role in making accurate and efficient decisions.

## Conclusions
**Model Training approach and Results**

###Insights from validation dataset
#####From the classification report we can draw the below insight:
- Random Forest emerges as the best model for fake news detection in this study.
	- It achieved the highest accuracy (96%), strong recall and precision for both fake and true news, and overall robustness.
- Logistic Regression is a good baseline, easy to interpret, but slightly less accurate.
- Decision Tree alone is not as reliable due to lower accuracy and overfitting tendencies.
- Recommendation: Use Random Forest for deployment if predictive performance is the priority. If explainability is crucial, Logistic Regression could complement it as a secondary model.

## Technologies Used
- numpy version: 1.26.4
- pandas version: 2.2.2
- seaborn version: 0.13.2
- matplotlib version: 3.10.0
- sklearn version: 1.6.1
- jar
- re
- sklearn_crfsuite
- joblib
- random
- spacy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This is an assignment from upgrad.

## Contact
Created by [@chinmaya-jeet] - feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
