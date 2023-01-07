<p align="center"> 
</p>
<h1 align="center"> Bank Marketing Effectiveness Prediction </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

<p>In this project I explored the previous data in order to predict if the client will subscribe to a term deposit offered by the banking institution. The results were in the form of yes or no as it a classification model.</p>

**Tags: Classification, Python, Machine Learning, Data Science**

**Project Presentation** :- [Slideshow](https://docs.google.com/presentation/d/1rWVoCbuXKhK1U2skhDQCyZvvBmWIEbFEcRsI5yRk6Ck/edit?usp=sharing)

<h2> :floppy_disk: Problem Statement </h2>

The data is related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to assess if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The classification goal is to predict if the client will subscribe to a term deposit (variable y).

<h2> :book: Attribute Information </h2>

<h4>Bank Client data:</h4>
<ul>
  <li><b>age</b> - numeric</li>
  <li><b>job</b> - type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown').</li>
  <li><b>marital</b> - marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed).</li>
  <li><b>education</b> - (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')</li>
  <li><b>default</b> - housing: has a housing loan? (categorical: 'no','yes','unknown')</li>
  <li><b>loan</b> - has a personal loan? (categorical: 'no','yes','unknown')</li>
</ul>

<h4>Related with the last contact of the current campaign</h4>
<ul>
  <li><b>contact</b> - contact communication type (categorical: 'cellular','telephone')</li>
  <li><b>month</b> - last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')</li>
  <li><b>day_of_week</b> - last contact day of the week (categorical: 'mon','tue','wed','thu','fri')</li>
  <li><b>duration</b> - last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.</li>
</ul>

<h4>Other attributes</h4>
<ul>
  <li><b>campaign</b> - number of contacts performed during this campaign and for this client (numeric, includes last contact)</li>
  <li><b>pdays</b> - number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)</li>
  <li><b>previous</b> - number of contacts performed before this campaign and for this client (numeric)</li>
  <li><b>poutcome</b> - outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')</li>
  <li><b>age</b> - numeric</li>
</ul>

<h4>Output variable</h4>
<ul>
  <li><b>y</b> - has the client subscribed to a term deposit? (binary: 'yes','no')</li>
</ul>

<h2> :book: Steps involved doing this project</h2>

Import data from dataset and perform initial high-level analysis: look at the number of rows, look at the missing values, look at dataset columns and their values respective to the campaign outcome.

Clean the data: remove irrelevant columns, deal with missing and incorrect values, turn categorical columns into dummy variables.

Use machine learning techniques to predict the marketing campaign outcome and to find out factors, which affect the success of the campaign.

<h2> :clipboard: Conclusion</h2>

**1.** The 2nd quarter of the year has the highest number of subscriptions & Month of May has the maximum subscriptions.

**2.** Blue-collar, management and technician showed maximum interest in subscription.

**3.** Compared to married and single, Divorced people have less interest in term deposits.

**4.** People with secondary education followed by tertiary education were subscribed to term deposit.

**5.** Generally people who don't have credit in default are interested in a deposit. Majority of the people have a home loan but only few of them opted for a term deposit.

**6.** Cellular communication is seen as more effective in comparison to other communication types.

**7.** The calls with large duration have more tendency for conversion. Majority of people were not contacted previously before this campaign.

**8.** We can choose Support Vector Machine or KNN or Decision Tree to predict Effectiveness as all 3 of them are showing the same accuracy & F1- Score - (0.8824).

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

Kunika Gupta | Data Science Enthusiast | Python | Alteryx | MySql | Tablaeu | Excel | Machine Learning


<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kunika0927/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kunikagupta27)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@kunika.gupta27)
[![Resume Badge](https://img.shields.io/badge/resume-0077B5?style=for-the-badge&logo=resume&logoColor=white)](https://drive.google.com/drive/folders/1sM1uv2UDomAGUR6ayLgp_wMvkbSbcZIH?usp=share_link)

