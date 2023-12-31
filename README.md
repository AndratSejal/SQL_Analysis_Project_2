# SQL_Employees_Analysis_Project_2

### Description:
EMPLOYEES ANALYSIS PROJECT WITH SQL (MICROSOFT SQL SERVER)
SQL (Structured Query Language) is a powerful and standardized programming language used to manage and interact with relational databases. As a data analyst, SQL is an essential tool that enables you to access, query, and manipulate data efficiently.

With SQL, you can retrieve specific information from databases using SELECT statements, filter data with the WHERE clause, and sort results with ORDER BY. It allows you to perform data aggregation using functions like SUM, AVG, COUNT, and more, to analyze large datasets and derive meaningful insights.

As a data analyst, having a strong grasp of SQL empowers you to explore, clean, and transform data efficiently, leading to informed decision-making and valuable insights that drive business success.

In this project I will walk you through steps I took in bring out insight from the employees datasets.
The project describes how to analysis employees data for good performance and provide better services.

### Questions:

Q1.Update Sale_Price column of property_price_train_new with an increase of 15%  when the Sale_condition is Normal.

Q2.Increase the length of BsmtUnfSF column size by 30 characters from property_price_train_new.

Q3. In property_price_train_new, 
-- a) convert Quantity data type from numeric to character 
-- b) Add then, add zeros before the Quantity field.  

Q4.Write a MySQL query to print the observations from the columns “Brick_Veneer_Area” and “Brick_Veneer_Type” of the table “Property_Price_Train_new”, excluding the values “None” And “BrkCmn” from the column “Brick_Veneer_Type”.

Q5. Extract all negative values from the column “W_Deck_Area”.

Q6.Write a MySQL query to print the observations of the table “Property_Price_Train_new” where the values of the column “Brick_Veneer_Type” ends with “e” and contains 4 alphabets.

Q7. Replace NA values with 'Null' for column Pool_Quality and show result is new column 'Pool_Quality_new' 

Q7. Check Miscellaneous_Feature and Pool_Quality columns contains how many NA values. 

Q8 If Miscellaneous_Feature and Pool_Quality contains count of NA value greater than 80 delete those column.
    
Q9. Display size of each database in mysql server.

Q10. Display Brick_Veneer_Area, Exterior_Material, BsmtFinSF1 when remodel_year was between 1950 - 1976

Q11. Q1. Retrive Brick_Veneer_Area, Exterior_Material, BsmtFinSF1, Remodel_Year and Sale_Pricey from property_price_train_new table and display only those columns whose Sale_Price is greater than average Sale_Price.

Q12. Create view 'check_id' that contains columns employee_id , first_name , last_name and manager_id that is between 100 and 114.

Q13 Update view check_id and add new record in check_id.
-- --example(employee_id=121, first_name=Bob, last_name=Tan)
    
Q14. Delete record from check_id view where employee_id is 104

Q15. From employee_details retrieve only employee_id , first_name ,last_name phone_number ,salary, job_id where department_name is Contracting (Note
Department_id of employee_details table must be other than the list within IN operator.

Q16. Display first_name , last_name and department_id from table employee where location_id =1700 from department table.

Q17. From the table (employees_details) find employees (employee_id, first_name, last_name, job_id, department_id) where manager_id is equal to employee_id.

Q18. Check whether the email_id is valid or not from employee_details
