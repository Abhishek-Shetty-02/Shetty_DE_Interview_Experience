# Shetty_DE_Interview_Experience
"This repository captures my Data Engineer interview journey — the challenges faced, lessons learned, and milestones achieved — to inspire and guide others to approach their own interviews with confidence and determination."

# **Interview 01:**

  <p>

**Round 01:**

1. Could you please tell me libraries you worked in python?
2. Explain where you had used Oops concept in your project?
3. Explain about medallion architecture?
4. What is trigger and its types ? what is the usage of it ?
5. Water mark column without CDC and triggers?

Data Modelling:

1. Star Schema and Snowflake Schema
2. Why we need star schema instead snowflake schema
3. What can we achieve using snowflake schema
4. Explain Kimball Methodology
5. Data vault V/S key vault
6. Any experience in building application using python or java?
7. Snowflake warehouse -multi cluster usage

Scenario based Coding: By Using Snowflake:

1. Create a table Employees with all the required attributes.
2. Read a csv file: employees.csv from S3 bucket into Snowflake and
do data validation by using pyspark: Null checks, date Standardization and report the data validation.
3. Write a automation script for the above in python.

  </p>

# Interview 02:


Intro:

Coding:

1.	Find the anagrams

  words = ["eat", "tea", "tan", "ate", "nat", "bat"]

  Output: [['eat', 'tea', 'ate'], ['tan', 'nat'], ['bat']]

Code Explanation?

2.	Write a Transaction Class and one class method as Credit.
Explain how to write a same code for Multiple transactions happening at the same.

Code Explanation?
 
  
**SQL**

3. 

| ID | Desc                        |
|----|-----------------------------|
| 1  | Chair, Sofa, TV             |
| 2  | Chair, Chair, Sofa, TV, TV  |
| 3  | TV, TV, Sofa                |

**Output:**

| Desc  | Count |
|-------|-------|
| Chair | 3     |
| Sofa  | 3     |
| TV    | 5     |


4. Explain the PySpark Optimization Techniques that you were used in your project?
5. How do you decide which clusters to be used in your project? and what are types of the Clusters?
6. What is the use case of Delta Live Tables in Databricks?
7. What If a pull request was accidentally merged into the main branch? How will you approach?

# Interview 03:

  HR ROUND 01: Discussion on work experience
  
  MANAGER ROUND 02: PROJECT FLOW discussion
  
  CLIENT ROUND 03: PROJECT FLOW, Scenario based questions wrt Data factory AND Databricks and lot of questions from Hadoop ecosystem: HDFS, Hive Tables and Apache iceberg format.

# Interview 04:

HR Technical ROUND : 6-8 theory questions wrt technical databricks, spark optimizations and delta lake

FINAL TECHNICAL ROUND:

Intro:

Project Flow:

Coding: 4-5 Pyspark coding


# Interview 05:

HR ROUND: Discussion on work experience

Technical ROUND: Will be Updated

# Interview 06:

**Technical Round 01:**

 Will be Updated soon
 
**Technical Manager Round 02 (Walk-in):**

Intro:

Project Flow:

Scenario based Questions:
1.	How will pull data from azure SQL DB?
2.	how do you ingest data from 500 Tables?
3.	what are the cluster configurations for a large datasets?
4.	How to Build a real time scalable pipeline which ingesting 200 million records everyday?
5.	Explain different types of triggers?
6.	Job clusters vs All Purpose Clusters: Trade off
7.	Have you build or worked on ML pipelines? How to build scalable real time Glucose prediction ML pipeline?

# Interview 07:

**Technical Round 01:**
  
1.	how do you create flow from streaming source to delta lake?
2.	how do you integrate APIs?
3.	which activity you used for calling APIs?
4.	any other activies for calling API in adf?
5.	how you do pass the bay tokens here , most of api are authorization how do you manage?
6.	what is diff get meta data and look up activity?
7.	Difference between tuple and list?
8.	why tuple less memory?
9.	explain spark architecture in detail?
10. what is cluster in databricks
11. Difference between rank , dense rank & row_number
12. difference between start schema and snowflake schema?
13. what is difference deep clone and shallow clone in databricks?
14. how do you integrate key vault to databricks?
15. which authorization we use for unity catalog when mounting to data lake form databrick?
16. what are databricks connectors

**Coding Tasks:**

1. Python
   i/p: [123,456,988]

   o/p:[6,15,25]

3. SQL: Write a query for Inner, left and Right join for below tables

| A    | B    |
|------|------|
| 1    | 1    |
| 2    | 1    |
| 2    | 2    |
| 2    | null |
| null | 2    |
| 3    | 3    |
| 4    | 3    |

3. Find the top 3 customer who spend more on prod_id? Write both in SQL and Pyspark

| sale_id | product_id | customer_id | sale_date   | amount |
|---------|------------|-------------|-------------|--------|
| 1       | 101        | 1           | 2024-01-01  | 100    |
| 2       | 101        | 2           | 2024-01-02  | 200    |
| 3       | 101        | 1           | 2024-01-03  | 150    |
| 4       | 101        | 3           | 2024-01-04  | 300    |
| 5       | 101        | 2           | 2024-01-05  | 100    |
| 6       | 102        | 1           | 2024-01-06  | 200    |


4. If col1 and col2 are divisible 10, then add the values. else substract the values.
and also Handle null and zero values properly using pyspark

| col1 | col2 |
|------|------|
| 10   | 20   |
| 15   | 25   |
| 0    | 30   |
| null | 40   |
| 50   | null |
| 60   | 70   |


**Technical Manager Round 02(Walk-in):**

Coding: 2 SQL Queries and 1 Pyspark Coding

**SQL Queries:**

A). Write a query to interchange/Swap the Student values between 1st and 2nd
Student Table

| Id | Student_name |
|----|--------------|
| 1  | Alice        |
| 2  | John         |
| 3  | Charlie      |
| 4  | David        |
| 5  | Joe          |
| 6  | Joe Daiz     |

B). Make it Duplicate records and write a query


**Pyspark:**

Data = [(1,'john',24,12345),(2,'Steve',36,78945),(3,'Joseph',245621)]

Columns = ['id','name','Age','Salary']

Create a dataframe and then convert it into respective json values.


1.	Difference between Web activity and Web Hook Activity?
2.	Difference between Deep copy and Shallow Copy?
3.	Difference between Job clusters and All purpose clusters?
4. How do you handle when CI pipeline when fails?
5. Difference between Copy activity and Data flow activities?
6. Difference between list, tuple, and Dictionary?
7.

**Technical Client Round:**

1.	How did you implemented the data governance in your project?
2. What you do with bad data when you did the quality checks?
3. How many tables you registered in your unity catalog in your current project?
4. In Unity catalog, table data where it is referencing?
5. Difference between table and view in sql?
6. How do you handle null?
7. What is SCD type 2?
8. How you are calculating your current and historical records?
9. What is partitioning?
10. Difference between managed table and external table?

Scenario based Questions:

1.	Tell me if data bricks job is running slow how you will you optimize?

2. You are running query it is taking long time . what will be step you follow to debug it?

3. How do you handle incremental loads?

**Coding:**

**emp_staging table:**

| emp_id | emp_name | address |
|--------|----------|---------|
| 1      | a        | abc     |

**emp table:**

| emp_id | emp_name | address |
|--------|----------|---------|
| 1      | a        | deg     |

**SQL Queries:**

Write a query to handle the delta?

Write a query for merging these two tables?

How do you implement data quality checks?

How do you verify the duplicates?

Add column salary to emp table

**Python:**

check whether it's a palindrome or not?

value = "madam"

# Interview 08:

**Technical ROUND 01:**

Intro:

Project flow:

1.	which services did you use for batch and steaming sources?
2. how you were migrating data form bronze to silver?
3. how scheduling the pipeline?
4. why didn't you use databricks instead of data factory?
5. In databricks suppose you have written code, you want share it for Review?
6. Scenario: 1 File 10 Gb and 10 files 1 GB : cache v/s persistence and Why?
7. difference between count * and count 1
8. Explain Materialized view?
9. Normal views v/s Materialized Views
10. How you are storing historical data?
11. Storing Row wise and Column Wise data?
12. Separate Table
13. suppose: Table in SQL Capture every operation happened on any row? How
14. Same In databricks?

**SQL Query:**

1.	Find duplicates

| employee_name | department | salary |
|---------------|------------|--------|
| James         | Sales      | 3000   |
| Michaell      | Sales      | 4600   |
| Robertl       | Sales      | 4600   |
| Marial        | Finance    | 3000   |
| James         | Sales      | 3000   |
| Scott         | Finance    | 3300   |
| Jen           | Finance    | 3900   |
| Jeff          | Marketing  | 3000   |
| Kumar         | Marketing  | 2000   |
| Saifi         | Sales      | 4100   |
| Scotti        | Finance    | 3300   |

**Pyspark**

2. Write a Query for Deleting the Duplicate data: 

Input:

Table A:

1|~abc|~100

2|~ gef|~200

3|~jkl|~300

Output:

Table A

| id | name | value |
|----|------|-------|
| 1  | abc  | 100   |
| 2  | gef  | 200   |
| 3  | jkl  | 300   |


