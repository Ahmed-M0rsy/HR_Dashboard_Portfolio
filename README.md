# HR-Dashboard-Python-PowerBI

![image](https://github.com/Ahmed-M0rsy/HR_Dashboard_Portfolio/blob/main/HR_Dashboard-1.png)
![image](https://github.com/Ahmed-M0rsy/HR_Dashboard_Portfolio/blob/main/HR_Dashboard-2.png)

## Data Used

**Data** - HR Data with over 22000 rows from the year 2000 to 2020.

**Data Cleaning & Analysis** - Python (Jupyter NoteBook `Colab`)

**Data Visualization** - PowerBI

## Questions

1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job titles across the company?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by state?
10. How has the company's employee count changed over time based on hire and term dates?
11. What is the tenure distribution for each department?

## Summary of Findings

- There are more male employees
- White race is the most dominant while Native Hawaiian and American Indian are the least dominant.
- The youngest employee is 22 years old and the oldest is 59 years old
- 5 age groups were created (20-29, 30-39, 40-49, 50-59). A large number of employees were between 30-39 followed by 40-49 while the smallest group was 50-59.
- A large number of employees work at the headquarters versus remotely.
- The average length of employment for terminated employees is around 10 years.
- The gender distribution across departments is fairly balanced but there are generally more male than female employees.
- The Auditing department has the highest turnover rate followed by Legal. The least turn over rate are in the Marketing, Business Development, and Human Resource.
- A large number of employees come from the state of Ohio.
- The  percentage of change in employees has decreased over the years.
- The average active tenure for each department is about 10 years with Sales, and Research & Development having the highest and Legal, Auditing and Training having the lowest.

## Limitations

- Some records had negative ages and these were fixed during querying.
- Some termdates were far into the future and were not included in the analysis(1296 records). The only term dates used were those less than or equal to the current date.
