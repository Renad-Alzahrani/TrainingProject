# TrainingProject

Predicting bank’s clients subscribe for term deposit


Renad Ahmed Alzahrani
Jeddah,
 Saudi Arabia.


Abstract:
The goal of this project is to use classification models to predict if the bank’s clients will subscribe for term deposit through a phone call campaign. In addition, the idea of the project can be applied to any data from the market, to predict the results of a campaign that can increase the business revenue. Accordingly, the project will answer the following questions:
•	Are bank’s clients will subscribe?  
•	Is the bank’s phone call campaign will succeed?
•	Can the bank initiate potential campaigns in the future?

Data Discerption:
The data will be used in this project is from direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The data has been downloaded from Kaggle website under the name of “Bank Marketing Data Set”. The data has 20 attributes with 41188 instances: 9 Numeric, 10 Categorical ,1 Boolean.
The attribute information as follow:

•	bank client data:
1 - age (numeric)
2 - job: type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
3 - marital: marital status (categorical: 'divorced', 'married', 'single', 'unknown'; note: 'divorced' means divorced or widowed)
4 - education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')
5 - default: has credit in default? (Categorical: 'no','yes','unknown')
6 - housing: has housing loan? (Categorical: 'no','yes','unknown')
7 - loan: has personal loan? (Categorical: 'no','yes','unknown')

•	related with the last contact of the current campaign:
8 - contact: contact communication type (categorical: 'cellular','telephone')
9 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
10 - day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
other attributes:
11 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
12 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
13 - previous: number of contacts performed before this campaign and for this client (numeric)
14 - poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')


•	social and economic context attributes
15 - emp.var.rate: employment variation rate - quarterly indicator (numeric)
16 - cons.price.idx: consumer price index - monthly indicator (numeric)
17 - cons.conf.idx: consumer confidence index - monthly indicator (numeric)
18 - euribor3m: euribor 3 month rate - daily indicator (numeric)
19 - nr.employed: number of employees - quarterly indicator (numeric)

•	The target:
20 - y - has the client subscribed a term deposit? (binary: 'yes','no')

Data prepossessing and Models:
•	Split the data into train and test data sets 80/20
•	Converting categorical features to binary
•	Use Logistic Regression , Decision Trees, k-Nearest Neighbors
•	Model Evaluation and Selection

Tools:
•	Numpy and Pandas for data manipulation
•	Scikit-learn for modeling
•	Matplotlib and Seaborn for plotting

The MVP Goal
•	The MVP will be two of the models and their evaluation.

