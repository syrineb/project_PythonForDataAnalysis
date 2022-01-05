
# Project Python for Data Analysis : Spambase Data Set
Syrine Bouchelleghem and Hajar Azzouzi

## Tasks 
The goal of this project is to :
- visualize the link between the variables and the target by using different libraries.
- Testing Machine Learning models on the data set to predict the class of an email (use the scikit-learn library)
- Tranform the model into a Django API

## Description of the Data Set
Data Set is from : https://archive.ics.uci.edu/ml/datasets/spambase
4601 instances , 58 attributes
 SPAM E-MAIL DATABASE ATTRIBUTES :
- 57 float attributes 
 - 1 nominal {0,1} class attribute of type spam = denotes whether the e-mail was considered spam (1) or not (0)

## Our work 
Visualizations of the raw data can be found in the file visualization.ipynb.
The models we tested are in modeling.ipynb

### Run the API 
- download api.zip and unzip
- open new terminal
- go to working directory 
- ```python manage.py runserver```
You will be able to enter an email and the api will be predict if it is a spam or not (return 1 if spam, 0 if not)
