# Fraudulent Claim Detection

> Logistic Regression and Random Forest model building for Fraudulent Claim Detection


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem
- Global Insure, a leading insurance company, processes thousands of claims annually. However, a significant percentage of these claims turn out to be fraudulent, resulting in considerable financial losses. The company’s current process for identifying fraudulent claims involves manual inspections, which is time-consuming and inefficient. Fraudulent claims are often detected too late in the process, after the company has already paid out significant amounts. Global Insure wants to improve its fraud detection process using data-driven insights to classify claims as fraudulent or legitimate early in the approval process. This would minimise financial losses and optimise the overall claims handling process.
### Dataset
- We are using the csv dataset which contains Fraudulent Claim Detection of 1000 rows and 39 columns

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Fraud cases are associated with higher claim amounts
- incident_type, insured_relationship, and authorities_contacted are important predictors
- Random Forest handles non-linear relationships better than Logistic Regression



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pytthon versio: 3.x
- NumPy version: 1.26.4
- Pandas version: 2.2.2
- Matplotlib version: 3.8.4
- Seaborn version: 0.13.2
- sklearn: 1.4.2
- imblearn: 0.12.3
- statsmodels: 0.14.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->