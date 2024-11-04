# LITA_Projects

### Project Title: Subscription Report Analysis

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

---
### Project Overview
This Data Analysis Project gives an insight into the type of subscription made over the years.By analysing various parameters in the data received ,we seek to gather enough insight to take into consideration the Subscription Type and Region the company derived the highest revenue and in what quarter of the year

---
### Data Sources
The primary source of the data used here was Given to us by Incubator Hub to test our level of understanding based on  what we were taught over the last 3 months 

---
### Tools Used
- Microsoft Excel [Downlaod Here](https://www.microsoft.com)
   * For Data cleaning
   * For Analysis
- Power BI
   * For Data Visualization 
- SQL - Structured Query Language
   * For quering data 
- GitHub
   * For Portfolio Building
---
### Data Cleaning and Preparation
In the initial phase of data cleaning and preparation,we perform the following action;
1. Data loading and inspection
2. Removing Duplicates
3. Handling missing data
4. Data cleaning and formatting
---
### Exploratory Data Analysis
EDA involved the exploring of the data to answer some questions such as ;
1. What is the total number of subscriptions made in a year ?
2. The total revenue derived from each subscription in various region ? 
3. Percentage of subscription that were canceled 
---
### Data Analysis
Some basic lines of code or queries used during analysis
  ``` SQL
SELECT TOP 3 SUM(Revenue) TOP_3,Region
FROM [dbo].[LITA Capstone Dataset (work2)]
GROUP BY Region
ORDER BY SUM(Revenue) DESC
```
![Table (2)](https://github.com/user-attachments/assets/8a7d1ca2-9f94-4c5f-a74e-821dcfdd2896)

---
### Data Visualization
![Subscription Report Overview_page-0001](https://github.com/user-attachments/assets/03eb0659-0588-437a-8c59-f1405452c639)
