# Analyzing borrowers’ risk of defaulting

### Background

This project is part of the Data Scientist training program from Practicum by Yandex. More info in link below:

https://practicum.yandex.com/data-scientist 

### Project Setup

This project is intended to prepare a report for a bank’s loan division. The goal is to find out if a **customer’s marital status and number of children** has an impact on whether they will default on a loan. The bank already has some data on customers’ credit worthiness.

This report will be considered when building a **credit scoring** of a potential customer. A **credit scoring** is used to evaluate the ability of a potential borrower to repay their loan.

**Data Description**

* children: the number of children in the family
* days_employed: how long the customer has been working
* dob_years: the customer’s age
* education: the customer’s education level
* education_id: identifier for the customer’s education
* family_status: the customer’s marital status
* family_status_id: identifier for the customer’s marital status
* gender: the customer’s gender
* income_type: the customer’s income type
* debt: whether the customer has ever defaulted on a loan
* total_income: monthly income
* purpose: reason for taking out a loan

**Conclusion**

The goal for this project was to make recommendations and insights to consider as the bank builds a credit score to assess potential customers. 

After my analysis, the bank should consider the following customer characteristics:
* if the customer has kids
* purpose of the loan
* age group
* gender
* marital status
* income type

These are the specific attributes that were found to correlate with higher default rates:
* Having 1-2 kids
* Taking out a loan for a car or education
* Being unmarried or in a civil partnership
* Being under 35 years old
* Being a male
* Being unemployed

The bank should not consider income level (total_income) as you determine a customer's credit score as there was no correlation between income and default rates.

**Technologies Used**

* Python (Pandas, Numpy, Seaborn)
* Docker

