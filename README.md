# ADS-505
ADS505 Final Project

Project Summary
This is a prediction algorithm model based on data from a Portuguese banking institution using a phone call-based marketing campaign. The objective is to predict whether the influence led to clients subscribing a term deposit.

Project Source
This is a public bank marketing dataset through UCI Machine Learning Repository. Moro, S., Cortez, P., & Rita, P. (2014). A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62, 22–31.

Predictor Variables
age (numeric)
job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student", "blue-collar","self-employed","retired","technician","services")
marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
education (categorical: "unknown","secondary","primary","tertiary")
default: has credit in default? (binary: "yes","no")
balance: average yearly balance, in euros (numeric)
housing: has housing loan? (binary: "yes","no")
loan: has personal loan? (binary: "yes","no")
contact: contact communication type (categorical: "unknown","telephone","cellular")
day: last contact day of the month (numeric)
month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
duration: last contact duration, in seconds (numeric)
campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
previous: number of contacts performed before this campaign and for this client (numeric)
poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")
Output variable (desired target):
y - has the client subscribed a term deposit? (binary: "yes","no")
Results
Random Forest Accuracy - .992 Precision - Remained Consistent at 11.5% Reduction of Resources by 30%
