# PWC Power BI Virtual work experience - Diversity and Inclusion

![image](https://github.com/MrutyunjayShukla/PWC-Power-BI-Virtual-work-experience-Users-Churn-Retention/assets/89764972/4946ec58-2462-4d15-9b86-4b91459ff7d6)


## Table of Content
- Problem Statement
- Importing Data
- Data Preparation
- Data Modelling
- DAX
- Data Visualization
- Insights

## Problem Statement
The purpose of this analysis is to:
- Define proper KPIs in hiring, promotion, performance and turnover
- Create a visualisation for the HR manager that reflects all relevant Key Performance indicators(KPIs) and metrics in the dataset.

## Importing Data
The Dataset was provided by PWC Switzerland.

## Data Preparation
Dataset was loaded into Power BI , Data was tranformed and loaded in Power Query editor.
- Validation of each coloumn Data Type's
- Removing Unnecessary Row's and Column's

# DAX
- % of employee promoted = CALCULATE(COUNTROWS('Pharma Group AG'),'Pharma Group AG'[Promotion in FY21?]="Yes")
- % promoted 20 = DIVIDE(COUNTA('Pharma Group AG'[Promotion in FY20?]),500)
- % promoted 21 = DIVIDE(COUNTA('Pharma Group AG'[Promotion in FY21?]),500)
- % turnover = [Turn Over]/500*1
- Turn Over = CALCULATE(COUNTROWS('Pharma Group AG'),'Pharma Group AG'[In base group for turnover FY20] = "Y")

## Data Modelling 
After the dataset was cleaned and transformed, The Data is ready for Modelling.

## Data Visualization 

### DashBoard

![I and D _1](https://github.com/MrutyunjayShukla/PWC-Power-BI-Virtual-work-experience-Diversity-and-Inclusion-/assets/89764972/d56cd5e9-e102-46b9-9f1e-e8d481647df9)

![I and D_2](https://github.com/MrutyunjayShukla/PWC-Power-BI-Virtual-work-experience-Diversity-and-Inclusion-/assets/89764972/88eb7cb5-2b1f-440f-b6bd-4513b9ff1fd6)

![I and D_3](https://github.com/MrutyunjayShukla/PWC-Power-BI-Virtual-work-experience-Diversity-and-Inclusion-/assets/89764972/720d4b3c-67cf-42ec-87a5-79dc64889c43)

## Insights
- 500 Employees are working, of which 295(59%) are male and 205(41%) are female employees.
- In FY 20, More Females were recruited than males, i.e.,  51.52%.
- In FY 20, More Males churn the company than females, i.e., 55.32%.
- There is decrease in rating for FY-20, from 2.57 to 2.41.
- The promotion has increased in Fy-20, from 7.20% to 10.20%.
- There are more male employees in high-level position such as Executive, Director, Senior manager.
- Female employees from Europe(50.73%).
- Male employees from Switzerland(57.29%).
- Males are more in Internal services, Sales and Marketing, Strategy, and Finance. (66.67%,64.88%,81.82%, and 66.67%)


