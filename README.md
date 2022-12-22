# Bank-Marketing-Effectiveness-Prediction-Classification-

This project will be explored over the previous data in order to predict if the client will subscribe to a term deposit offered by the banking institution. The results will be in the form of yes or no as it a classification model.

**Tags: Classification, Python, Machine Learning, Data Science**

**Links:**

**Project Presentation** :- [Slideshow](https://docs.google.com/presentation/d/1rGTdPkCRbSpQVaEzcS4-4Qb7lEKr05FLd8bCoge5N18/edit?usp=sharing)

## Problem Statement:
The data is related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to assess if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The classification goal is to predict if the client will subscribe to a term deposit (variable y).

## Attribute Imformation:
**Input variables:**
**Bank Client data:**

**age**
(numeric)

**job:**
type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')

**marital:**
marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)

**education:**
(categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')

**default:**
housing: has a housing loan? (categorical: 'no','yes','unknown')

**loan:**
has a personal loan? (categorical: 'no','yes','unknown')

## Related with the last contact of the current campaign:

**contact:**
contact communication type (categorical: 'cellular','telephone')

**month:**
last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')

**day_of_week:**
last contact day of the week (categorical: 'mon','tue','wed','thu','fri')

**duration:**
last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

## Other attributes:

**campaign:**
number of contacts performed during this campaign and for this client (numeric, includes last contact)

**pdays:**
number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

**previous:**
number of contacts performed before this campaign and for this client (numeric)

**poutcome:**
outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

## Output variable (desired target):

**y:**
has the client subscribed to a term deposit? (binary: 'yes','no')

## Steps involved doing this project

Import data from dataset and perform initial high-level analysis: look at the number of rows, look at the missing values, look at dataset columns and their values respective to the campaign outcome.

Clean the data: remove irrelevant columns, deal with missing and incorrect values, turn categorical columns into dummy variables.

Use machine learning techniques to predict the marketing campaign outcome and to find out factors, which affect the success of the campaign.

## Conclusion:

**1.** The 2nd quarter of the year has the highest number of subscriptions & Month of May has the maximum subscriptions.

**2.** Blue-collar, management and technician showed maximum interest in subscription.

**3.** Compared to married and single, Divorced people have less interest in term deposits.

**4.** People with secondary education followed by tertiary education were subscribed to term deposit.

**5.** Generally people who don't have credit in default are interested in a deposit. Majority of the people have a home loan but only few of them opted for a term deposit.

**6.** Cellular communication is seen as more effective in comparison to other communication types.

**7.** The calls with large duration have more tendency for conversion. Majority of people were not contacted previously before this campaign.

**8.** We can choose Support Vector Machine or KNN or Decision Tree to predict Effectiveness as all 3 of them are showing the same accuracy & F1- Score - (0.8824).
