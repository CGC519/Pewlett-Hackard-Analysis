# Pewlett-Hackard-Analysis
Using SQL and PGAdmin to analyze the employee database and retiring employees.
## Resources Used
* PGAdmin 
* SQL
* PostGreSQL
* Original datasets from csv files 
  * departments.csv
  * dept_emp.csv
  * dept_manager.csv
  * employees.csv
  * salaries.csv
  * titles.csv

# Overview of the Analysis
Hewlett Packard is wanting us to perform some data wrangling to determine who is about to retire or getting close to retiring. They have labeled this natural occurrence the "silver tsunami", where a surge of many current employees will all start retiring at the same time. They would like to be prepared for the impact this will have on the company by identifying where this will hit the hardest. They would also like to know who will be eligible for the upcoming mentorship program. 
# Results
* First we had to identify the ERD map of how the databases should relate to each other. I started by creating a visual to help guide me through the process. 

![EmployeeDB png](https://user-images.githubusercontent.com/108694898/205473706-c19754ce-c6a5-49fb-a909-6ae8963f0f18.png)

* Upon review of our databases, we were able to determine that out of the **300,024 employees** within the company, **90,398** (30.13%) are eligible for retirement.
* When we looked into the mentorship program we determined there were **1,549 employees** eligible for the program. 
# Summary 
Overall we can see that 30% of the employees are eligible for retirement and that will be a huge loss of workforce to the company. We can only suggest that they start to hire more employees to assist with the transition of roles. 
