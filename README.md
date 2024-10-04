
# HR Data Analysis Project

## Project Overview

This project showcases data analysis using SQL on an HR dataset. The goal of the analysis is to extract valuable insights related to employee demographics, job satisfaction, attrition rates, and more. Each SQL query addresses a specific business question aimed at helping HR managers make data-driven decisions.

## Dataset

The dataset, `hrdata`, contains various attributes related to employees, including:

- **Department**: The department to which an employee belongs (e.g., Sales, R&D).
- **Job Role**: The specific job role of the employee within a department.
- **Age**: The age of the employee.
- **Education**: The education level of the employee (e.g., High School, Bachelor’s, Master’s).
- **Job Satisfaction**: Job satisfaction rating of the employee (scale of 1 to 5).
- **Attrition**: Whether the employee has left the company (Yes/No).
- **Business Travel**: Frequency of business travel for the employee.
- **Marital Status**: The marital status of the employee (Married/Single/Divorced).
- **Age Band**: Categorized age groups to analyze trends by age.

## SQL Queries Breakdown

1. **Count the number of employees in each department**  
   _Query:_ Retrieves the number of employees working in each department.

2. **Calculate the average age for each department**  
   _Query:_ Provides the average age of employees within each department to understand age distribution.

3. **Identify the most common job roles in each department**  
   _Query:_ Analyzes job roles and highlights the most common ones for each department.

4. **Calculate the average job satisfaction for each education level**  
   _Query:_ Computes the average job satisfaction score for employees based on their education level.

5. **Determine the average age for employees with different levels of job satisfaction**  
   _Query:_ Provides insights into the relationship between age and job satisfaction.

6. **Calculate the attrition rate for each age band**  
   _Query:_ Helps understand which age groups have the highest attrition rates.

7. **Identify departments with the highest and lowest average job satisfaction**  
   _Query:_ Highlights which departments have the most and least satisfied employees on average.

8. **Find the age band with the highest attrition rate among employees with a specific education level**  
   _Query:_ Identifies which age and education groups are most likely to leave the company.

9. **Find the education level with the highest average job satisfaction among employees who travel frequently**  
   _Query:_ Investigates how education level correlates with job satisfaction for employees who travel frequently.

10. **Identify the age band with the highest average job satisfaction among married employees**  
   _Query:_ Provides insights into how age and marital status affect job satisfaction.

## Usage Instructions

To run the SQL queries, follow these steps:

1. **Set up the Database**  
   Ensure that you have a MySQL or similar SQL environment set up on your local machine or server. Import the `hrdata` dataset into your SQL environment using the following command:

   ```sql
   USE hr_data;
   ```

2. **Run the Queries**  
   Copy and paste each SQL query from this repository into your SQL environment to execute the analysis. Each query is designed to answer a specific business question related to HR metrics.

3. **Modify Queries**  
   Feel free to modify the queries or dataset as per your requirements. For example, you could add additional filters, groupings, or conditions to tailor the analysis to your own dataset or business scenario.

## Future Enhancements

- Include visualizations for the results of the SQL queries.
- Extend the analysis to cover other HR metrics such as performance ratings and promotions.
- Implement stored procedures for reusable query patterns.

## Conclusion

This project demonstrates how SQL can be used to analyze HR data for valuable insights into employee behavior, satisfaction, and attrition trends. With these insights, companies can make informed decisions regarding employee retention and satisfaction strategies.

---

## Contact

For any questions or suggestions, feel free to reach out via GitHub or email.
