# SQL_HackerRank_Challenges

SQL>Basic Select>Employee Salaries

Write a query that prints a list of employee names (i.e., the name attribute) for employees
in Employee having a salary greater than $2000 per month who have been employees for 
less than 10 months. Sort your results by ascending employee_id.

Input Format

The Employee table containing employee data for a company is described as follows:

![image](https://user-images.githubusercontent.com/104165655/167508293-dee087d6-7ee6-437a-a329-c2e2d7c4284a.png)

where employee_id is an employee's ID number, name is their name, months is the total 
number of months they've been working for the company, and salary is their monthly salary.

SOLUTION:

SELECT name
FROM Employee
WHERE salary > 2000
AND months < 10
ORDER BY employee_id ASC;
