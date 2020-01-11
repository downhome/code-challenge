### Class Averages

Choose 3 questions to answer from the list below.  A school district keeps track of all students within the district by keeping track of every student in every class in every school within the district.  They decided to hire a YOU as the SQL master who would be able to answer the following questions for them. 

Write SQL queries (MySql, Postgresql, Oracle, MS SQL, ...etc) that answers the following questions:

1. How many students are in each school?
2. What is the highest, lowest and average score for **EACH** school?
3. What is the highest, lowest and average score for **ALL** the schools?
4. What school has the highest score, and what is the highest score?
5. What schools has the lowest score, and what si the lowest score?

Students Table

| Column           | Type         |
| :--------------- | :----------- |
| identifier       | varchar(5)   |
| name             | varchar(20)  |
| Score            | decimal(8,2) |
| class_identifier | varchar(5)   |



Class Table

| Column     | Type        |
| :--------- | :---------- |
| identifier | varchar(5)  |
| location   | varchar(20) |
| school     | varchar(20) |

