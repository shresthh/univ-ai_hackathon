## univ-ai_hackathon

Problem Statement

An organization wants to predict who possible defaulters are for the consumer loans product. They have data about historic customer behavior based on what they have observed. Hence when they acquire new customers they want to predict who is more risky and who is not.

Submissions will be evaluated on the basis of roc_auc_score. Only the last submission will be considered for the leaderboard.

Column
Description
Type
income	Income of the user	int
age	Age of the user	int
experience	Professional experience of the user in years	int
profession	Profession	string
married	Whether married or single	string
house_ownership	Owned or rented or neither	string
car_ownership	Does the person own a car	string
risk_flag	Defaulted on a loan	string
current_job_years	Years of experience in the current job	int
current_house_years	Number of years in the current residence	int
city	City of residence	string
state	State of residence	string


Participated in UNIV.ai hackathon and tried different models for classification.
1. Did feature engineer on data.(scaled, normalized, and label encoded)
1. Tried models includes Random Forest, Lightgbm, XGBOOST.Also used pycaret library to compare all the models.
2. Used pycaret to find feature importance.
3. Got best accuracy of 84+% with Random Forest.
