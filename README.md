# Use Case Summary
  ## Objective Statement: 
-  Get an insight about what is the effect of salary on the employee
-  Get an insight into which department has the lowest salary
-  Get an insight into what department most leave the company
-  Get an insight about how satisfaction employees who left the company

  ## Analytisc Technique:
- Descriptive Analysis
- Graph Analysis

  ## Expected Outcome:
-  Know what is the effect of salary on the employee
-  Know the name of a low-paying company department
-  Know what department most leave the company
-  Know how satisfaction employees who left the company 

# Business Understanding
-  This dataset contains a company that records various employee parameters (example : salary, satisfaction level, etc).
-  This case contains some business questions based on the data:
      -  What is the effect of salary on the employee?
      -  Which department has the lowest salary?
      -  What department most leave the company?
      -  How satisfaction employees who left the company?

# Data Understanding
-  Source data by Kaggle
-  Data Dictionary:   
      - statisfaction_level: satisfaction level at the job of an employee
      - last_evaluation: rating between 0 to 1 received by an employee at this last evaluation
      - number_project: number of projects an employee involved 
      - average_monthly_hours: average number of hours in a month, spent by an employee at the company
      - time_spend_company: number of years spent in the company
      - Work_accident : 0 = no accident during employee stay, 1 = accident during employee stay
      - left : 0 = indicates employee stay in the company, 1 = indicates employee left the company
      - promotion_last_5year: number of promotions in his stay
      - Department: department an employee belongs to
      - salary: salary in USD

# Data Preparation
-   Packages : Pandas, Numpy, Seaborn, Matplotlib
-   Use HR comma sep dataset
      - All columns, except sales and salary columns are numeric.
      - Work_accident, left, and promotion_last_5years are binary (0,1).
      - The name of the sales column will be changed to Department.
# Data Cleansing
-   The dataset has no missing values, and the data type names are all correct.
-   The dataset contains 3008 duplicated data points that must be removed.

# Exploratory Data Analysis
What is the effect of salary on the employee?
Many employees leave the company because their salary is low and medium

![image](https://user-images.githubusercontent.com/95860293/155239387-01f510cf-99e5-49e8-aaf7-d80ae81dce1b.png)

Which department has the lowest salary?
sales, technical and support departments have low and medium salary

![image](https://user-images.githubusercontent.com/95860293/155239418-45ba9dac-1191-48d0-9fea-27b1f5a395bb.png)

What department most leave the company?  
The sales department has the most employees who leave the company, followed by the technical and support departments

![image](https://user-images.githubusercontent.com/95860293/155239476-bac9812f-7c01-4116-a7ac-71687f1169fa.png)

How satisfaction employees who left the company?
The highest number of employees leaving a company with a low satisfaction rate is below 20%

![image](https://user-images.githubusercontent.com/95860293/155239510-2fe79bd2-1571-4ea4-a973-5c5dcb1e3af3.png)


# Conclusion
In the dataset, fewer employees are leaving the company, which is 1991 employees and 10000 employees remain in the company. 
The analysis focuses on employees leaving the company, with salaries having a significant impact on the number of          employees leaving the company. Employees who are paid more in the low and medium ranges are more likely to leave     the company.
The lowest and medium salaries were found in the sales, technical, and support departments.
The highest number of employees who left the company came from sales departments of 3239 employees, technical      departments of 2244 employees, and support departments of 1821 employees. 
Employees who leave the company have  an average satisfaction rate of less than 50% and the highest number with the lowest satisfaction level is less than 20%.
