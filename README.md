# SQL-Queries

## In this lab we practice SQL queries with filters AND, OR and NOT, also including LIKE and % to get the information we need in every exercise.

### Task 1. Retrieve after hours failed login attempts
Your team is investigating failed login attempts that were made after business hours. You want to retrieve this information from the login activity. You’ll identify all unsuccessful attempts after 18:00.

The login_time column in the log_in_attempts table contains information on when login attempts were made. Office hours end at '18:00'.

The success column in the log_in_attempts table contains values of TRUE or FALSE to indicate whether the login was successful. MySQL stores Boolean values as 1 for TRUE, and 0 for FALSE. This means that TRUE is represented as 1, and FALSE represented as 0 in the success column.

Use the AND operator to retrieve the failed login attempts that occurred after business hours. Replace the X and Y with the correct values to filter for the records you need.

To get the results asked we need to do a query with the following filters:

![image](https://imgur.com/kqAEZue.png)

![image](https://imgur.com/vSFJOps.png)

### Task 2. Retrieve login attempts on specific dates
Your team is investigating a suspicious event that occurred on '2022-05-09'. You want to retrieve all login attempts that occurred on this day and the day before '2022-05-08'.

The login_date column in the log_in_attempts table contains information on the dates when login attempts were made.

Use the OR operator to retrieve the failed login attempts on the specified days.

To get the results asked we do the following query.

![image](https://imgur.com/j2cJ04p.png)

![image](https://imgur.com/NQxwhN0.png)

![image](https://imgur.com/WavTj6h.png)

### Task 3. Retrieve login attempts outside of Mexico
Now, your team is investigating logins that did not originate in Mexico, and you need to find this information. Note that the country field includes entries with 'MEX' and 'MEXICO'. You should use the NOT and LIKE operators and the matching pattern 'MEX%'.

Run the following SQL query to retrieve login attempts that did not originate in Mexico.

![image](https://imgur.com/HiqXitf.png)

![image](https://imgur.com/Rmvmvlf.png)

![image](https://imgur.com/klygHEg.png)

### Task 4. Retrieve employees in Marketing
For tasks 4, 5 and 6 you need to retrieve the information from the department and office columns in the employees table.

Your team is updating employee machines, and you need to obtain the information about employees in the 'Marketing' department who are located in all offices in the East building (such as 'East-170' or 'East-320').

Write a SQL query to retrieve this information from the employees table. Select all columns and include filters on the department and office columns to return only the needed records.

![image](https://imgur.com/m3cgkR2.png)

![image](https://imgur.com/Qo6F9cS.png)

### Task 5. Retrieve employees in Finance or Sales
Now, your team needs to perform a different update to the computers of all employees in the Finance or the Sales department, and you need to locate information on these employees.

Write a SQL query to retrieve records for employees in the 'Finance' or the 'Sales' department.

![image](https://imgur.com/s54pAoy.png)

![image](https://imgur.com/XFBWc86.png)

### Task 6. Retrieve all employees not in IT
Your team needs to make one more update. This update was already made to employee computers in the Information Technology department. The team needs information about employees who are not in that department. You should use the NOT operator to identify these employees.

Write a SQL query to retrieve records for employees who are not in the 'Information Technology' department.

![image](https://imgur.com/uLLgyg2.png)

![image](https://imgur.com/2t7mHSu.png)

In this lab we learned how to do queries in SQL with different filters to either get more information or not get information that we do not need making our queries more efficient and less time consuming.
