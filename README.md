# HR-EMPLOYEE-DISTRIBUTION-REPORT
Hello everyone!
I have created interactive Dashboard on HR Analytics using Power BI and MY SQL Workbench.

## **Project Objective**
To create and present a comprehensive HR Employee Distribution Report that provides a detailed analysis of the workforce distribution within the organization. The report aims to offer valuable insights into various aspects of employee distribution, facilitating informed decision-making and strategic workforce planning.

## **Getting Started**
To view and interact with the dashboard, you'll need **Power BI Desktop**. You can download and install it from the Microsoft Store or by following this link(https://www.microsoft.com/en-us/download/details.aspx?id=58494).

## **Data Source**

The data is stored in CSV format. The following steps were followed in the project:

1. **Extract the Data**:
 The sales data was extracted from the provided CSV files.
2. **Data Cleaning & Analysis**:
 MY SQL Workbench.
3. **Data Visualization**:
 PowerBI

 ## **Performance Indicators (KPIs)** – 
1. What is the gender breakdown of employees in the company?
2. What is the race breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of employees across locations by state?
8. What is the tenure distribution for each department?

 ## **Dashboard**
![HR Employee Distribution](https://github.com/Aryan18107/HR-EMPLOYEE-DISTRIBUTION-REPORT/assets/156915129/dd555229-9d74-4785-a0ae-3606d3b98e4b)

 ## **Project Insight**
1. There are more male employees
2. White race is the most dominant while Native Hawaiian and American Indian are the least dominant.
3. The youngest employee is 20 years old and the oldest is 58 years old
4. 4 age groups were created (18-30, 31-42, 43-54, 55-66). A large number of employees were between 31-42 followed by 43-54 while the smallest group was 55-66.
5. A large number of employees work at the headquarters versus remotely.
6. The average length of employment for terminated employees is around 8 years.
7. The gender distribution across departments is fairly balanced but there are generally more male than female employees.
8. A large number of employees come from the state of Ohio.
9. The average tenure for each department is about 8 years with Sales having the highest 9 years, Business development, Human Resource, Legal, Product Management, Support, Training having lowest 7 years.

## **Limitations**
1. Some records had negative ages and these were excluded during querying(967 records). Ages used were 18 years and above.
2. Some termdates were far into the future and were not included in the analysis(1599 records). The only term dates used were those less than or equal to the current date.









