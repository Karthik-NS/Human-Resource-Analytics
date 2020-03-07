# Human-Resource-Analytics
Human Resource Analytics Using Hive

Objective
Ingest HR data from mysql database using sqoop into HDFS and then using Hive analyze the Human resource data set and generate various insights about why are our best and most experienced employees leaving prematurely?
Data Description
 Satisfaction_level
 Last evaluation
 Number of projects
 Average monthly hours
 Time spent at the company
 Whether they have had a work accident
 Whether the employee has left
 Whether they have had a promotion in the last 5 years
 Department
 Salary

KPIs
1. Average satisfaction_level for individual Department.
2. How many employees are left in each individual Department?
3. Department wise average monthly working hour.
4. No of Project done by individual Department.
5. Department wise salary Distribution.
6. In individual Department How many Employees promoted in last 5 years but still left the company.
7. Department wise average satisfaction level, average working hours and no of employee who left company.
8. When salary is low find out the Department wise mean satisfaction level , average working hours and no of employee who left company.
9. When salary is low and not promoted in last 5 year than find out the Department wise mean satisfaction level, average working hours and no of employee who left company.
10. For individual department find out the average satisfaction_level, average evaluation and percentage of employees left company on the basis of salary.
11. How many employees left, distribution based on experience.
12. Name of the department where more than 70% employees left the company.
13. Highly experienced employee in each department.
14. Salary Distribution of highly experienced employee in company.
15. In which department total no of project is greater than 40% of overall project.

Note: KPI 15 will be intersting, we cannot solve this using regular nested sql queries. Hence we need to use analytic functions.
