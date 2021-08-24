# Exploratory Data Analysis on Bank Loan Applications: Project Overview
---
* Identify the patterns which indicates if a client has difficulty paying their installments
* Understanding the driving factors (or driver variables) behind loan default
* Finding consumer attributes and loan atrribites influence the tendency of default

## Code and Resources Used
---
**python version:** 3.7 <br>
**Packages:** pandas, numpy, matplotlib, seaborn

## Data Cleaning
---
* Identifying **missing values** in the data
* dropping records which having more than `30% mising values`
* making days columns to positive using **abs()** function
* Changing the type of the numeric columns from `object` to `int`  
* **Imputing missing values** with mean of that columns
* created age column with use of days_birth to represent age in terms of 

## EDA
---
### Univariate Analysis 
**categorical - categorical**
* On visualizing categorical variables find that **married people are most likely to apply for loans**
* On box potting age of the cutomers, people applying for loan with **age greater than 40 are more likely to repay loan**

### Bivariate Analysis
**continous - categorical**
* Data suggests **students** category are with **no defaulters** from past to present
* customers with `higher education` and with `annuity` is more thna `60,000` are likely to get `defaulted`




 
