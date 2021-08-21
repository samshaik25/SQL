# **SQL**
---
## What is SQL ?

* SQL stand for structured query language
* SQL is a standard language for accessing and manipulating database

## What can SQL do ?

  * SQL can execute queries against a database
  * SQL can retrieve data from a database
  * SQL can insert records in a database
  * SQL can update records in a database
  * SQL can delete records from a database
  * SQL can create new databases
  * SQL can create new tables in a database
  * SQL can create stored procedures in a database
  * SQL can create views in a database


  ## **SQL Syntax** :

  ## Database Tables 

  A database most often contains one or more tables. Each table is identified by a name (e.g. "Customers" ). Tables contain records (rows) with data.

 Below is a selection from the "Customers" table:
  
  |Customer Name | Contact| Adress |City |
|:------------|:------- |:--------| :------|
|Shaik Sameer | 8309314677 | Street : 22 | Hyderabad |
| Tarun | 7733445982 | 1-7/2 | Nizamabad |
| Rohit Kumar | 8833090123 | Times square | Bangalore|

### The following SQL statement selects all the records in the "Customers" table:
``` 
SELECT * FROM Customers;
```

# Some of The Most Important SQL Commands :

* **SELECT** - extracts data from a database
* **UPDATE** - updates data in a database
* **DELETE** - deletes data from a database
* **INSERT INTO** - inserts new data into a database
* **CREATE DATABASE** - creates a new database
* **ALTER DATABASE** - modifies a database
*  **CREATE TABLE** - creates a new table
*  **ALTER TABLE** - modifies a table
 * **DROP TABLE** - deletes a table
 * **CREATE INDEX** - creates an index (search key)
 * **DROP INDEX** - deletes an index


---
---
# **SQL JOIN**
---
A JOIN clause is used to combine rows from two or more tables, based on a related column between them.DIfferent types of JOINS are :

*  Self Join :self join is a regular join, but the table is joined with itself.
* INNER JOIN : Returns records that have matching values in both tables
 * LEFT JOIN : Returns all records from the left table, and the matched records from the right table
 *   RIGHT JOIN :  Returns all records from the right table, and the matched records from the left table
*  FULL JOIN : Returns all records when there is a match in either left or right table

![](data:image/jpeg;base64,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)



 ## __INNER JOIN Syntax__
``` 
SELECT column_name(s)
FROM table1
INNER JOIN table2
ON table1.column_name = table2.column_name;
```
## **LEFT JOIN Syntax**
``` 
SELECT column_name(s)
FROM table1
LEFT JOIN table2
ON table1.column_name = table2.column_name;
``` 
## **RIGHT JOIN Syntax**
``` 
SELECT column_name(s)
FROM table1
RIGHT JOIN table2
ON table1.column_name = table2.column_name;
``` 


## **FULL OUTER JOIN Syntax**
``` 
SELECT column_name(s)
FROM table1
FULL OUTER JOIN table2
ON table1.column_name = table2.column_name
WHERE condition; 
```
### **EXAMPLES OF JOINS WITH TABLES**
consider we have two tables named *tblCountry* and *tblState* as follows
| CountryID | CountryName|             
|:------------|:------- |
|1|India|
|2|Nepal|
|4|Srilanka|


| StateID | CountryID|   Statename|           
|:------------|:------- |:------- |
|1|1|Maharasta|
|2|1|Punjab|
|3|2|Kathmandu|
|4|NULL|California|
  
> *INNER JOIN*:
  ```
  select * from tblCountry
  inner join tblState
  on tblCountry.countryID=tblState.CountryID
  ```
   The result of *INNER JOIN* will be :
| CountryID |CountryName | StateID | CountryID | StateName|
  |----------|------------|---------|----------|-----------|
  |   1       | India          |  1         |   1      | Mahrastra   |
  |   1       | India          |  2         |   1      | Mahrastra    |
  |   2       | Nepal          |   3        |   2      | Kathmandu    |


 
 > *LEFT JOIN*
 ```
  select * from tblCountry
  left join tblState
  on tblCountry.countryID=tblState.CountryID
  ```
  The result of *LEFT JOIN* will be :
| CountryID |CountryName | StateID | CountryID | StateName|
  |----------|------------|---------|----------|-----------|
  |   1       | India          |    1         |   1      | Mahrastra  |
  |   1       | India          |     2        |   1      | Punjab     |
   |   2     | Nepal           |     3        |   2      | Kathmandu  |
   |    4     |   Srilanka     |      NULL    |   NULL    |     NULL    |
 
  > *RIGHT JOIN*
 ```
  select * from tblCountry
  right join tblState
  on tblCountry.countryID=tblState.CountryID
  ```
  The result of *RIGHT JOIN* will be :
| CountryID |CountryName | StateID | CountryID | StateName|
  |----------|------------|---------|----------|-----------|
  |   1       | India          |    1         |   1      | Mahrastra  |
  |   1       | India          |     2        |   1      | Punjab     |
   |   2       | Nepal         |     3        |   2      | Kathmandu  |
   |    NULL   |   NULL        |     4         |   NULL    |   California  |


 > *FULL OUTER JOIN*
 ```
  select * from tblCountry
  full outer  join tblState
  on tblCountry.countryID=tblState.CountryID
  ```
  The result of *FULL OUTER JOIN* will be :
| CountryID |CountryName | StateID | CountryID | StateName|
  |----------|------------|---------|----------|-----------|
  |   1       | India          |    1         |   1      | Mahrastra  |
  |   1       | India          |     2        |   1      | Punjab     |
  |   2       | Nepal         |     3        |   2      | Kathmandu  |
  |   4       |  Srilanka     |     NULL    |   NULL    |   NULL  |
  |   NULL    |  NULL         |       4    |      NULL   |California  |

  FULL JOIN is a combination of all ,it matches everything irrespective of condition.


---
---
# **AGGREGATE FUNCTIONS**

---
In database management, an aggregate function or aggregation function is a function where the values of multiple rows are grouped together to form a single summary value.


  * **COUNT** counts how many rows are in a particular column.
  * **SUM** adds together all the values in a particular column.
   * **MIN and MAX** return the lowest and highest values in a particular column, respectively.
  * **AVG** calculates the average of a group of selected values.
  ### Below are the EXAMPLES :
   let us consider an *EMPLOYEE* Table
   | EMP_ID | EMP_NAME| DEPT |SALARY |
  |:---------:|:-------:|:--------:| :------:|
   |1|Sam|HR|100000|
   |2|Sham|IT|2000|
   |3|Ravi|MRKT|15000|
   |4|Kiran|IT|NULL
 ** Here the *NULL* means value is *NOT DEFINED* 

  1. *MAX*: To find the MAXIMUM salary from the *EMPLOYEE* table
     * **SYNTAX**
      ```
        SELECT Max(SALARY) from EMPLOYEE;
      ```
      Here the output will be **100000**
  1. *MIN*: 
     * **SYNTAX**
      ```
        SELECT Min(SALARY) from EMPLOYEE;
      ```
      Here the output will be **2000**
1. *COUNT*;
    * **SYNTAX**
     ```
     SELECT Count(*) from EMPLLOYEE;
     ```
     It gives how many *ROWS* are present in the table
      ```
      SELECT Count(SALARY) from EMPLLOYEE;
      ```
      The above Syntax gives output **3**. It doesn't count the *NULL*
      ```
      SELECT Distint(Count(SALARY)) from EMPLLOYEE;
      ```    
      The above Syntax only counts *DISTINCT* values and the *NULL* doesnt gets counted.
      
1. *SUM*
    * **SYNTAX**   
     ```   
      SELECT Sum(SALARY) from EMPLOYEE;
      ``` 
     The above syntax will give tatal salary value.

1. *AVG*
    ```
   SELECT Avg(SALARY) from EMPLOYEE;
    ```
    The above syntax will give Average of salary.
 
> [LINKS USED FOR DOCUMENTATION ](https://www.w3schools.com/sql/sql_join.asp)

> [LINKS USED FOR DOCUMENTATION](https://www.w3schools.com/sql/sql_min_max.asp)
