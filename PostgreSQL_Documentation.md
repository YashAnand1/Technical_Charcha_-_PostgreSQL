<center>

# Documentation: PostgreSQL Tasks        
### — Database, Tables & Queries —    

_____________________________________________________________________________________                        

#### <u>INDEX</u>  

</center>  

Understanding & Setting-Up PostgreSQL                     
PostgreSQL: Q&A                       
TASK I: Create DB & Sample Table                                                
TASK II: Retrieve Table Data Using SQL Queries                          

<center>      

_____________________________________________________________________________________      

</center>
   

<center>

## Understanding & Setting-Up PostgreSQL

</center>

PostgreSQL or Postgres is a relational database management system (RDBMS). The data is organised here into tables with rows and columns. Additionally, the storing and retrieving of data is done using SQL on the basis of the relation between tables.

<center>

![image](https://ashnik-images.s3.amazonaws.com/prod/wp-content/uploads/2021/02/20050444/Postgresql-w-400x106.png)
</center>

Some of the main features of Postgre include:   
- Storage & management of structured data 
- Efficient retrieval capabilities
- SQL for interacting with DB 

On my system, the installation of Postgres was done using this [YouTube Tutorial](https://www.youtube.com/watch?v=-LwI4HMR_Eg). For reference, I have created a demonstration of the steps utilised for installing and setting-up Postgres locally on my system, as a video below:
<center>

</center>


The steps followed for the setting-up Postgres were as follows: 
- Updating the system repositories using **`sudo apt update`**
- Installing PostgresSQL & additional utilities using **`sudo apt-get install postgresql postgresql-contrib`**
  ```
  Output:
  ```
- Checking the status of Postgres using **`service postgresql status`**
   ```
  Output:
  ```
- Entering Postgres using **`sudo su postgres`**
    ```
  Output:
  ```
- Launching PSQL terminal for interacting with the database using **`psql`**
    ```
  Output:
  ```
- Creating user with **`CREATE USER yashanand WITH PASSWORD 'a';`**
    ```
  Output:
  ```
- Adding Superuser privilege to the new user using **`ALTER USER yashanand WITH SUPERUSER;`**
   ```
  Output:
  ```




--------------------------------
<center>

## PostgreSQL: Q&A    

</center>

After gaining a basic understanding and a working set-up of Postgres, I worked on giving answers to the 'True or False' questions as a part of our first assignment. It should be noted that these questions were based on the 'Technical Charcha On PostgreSQL' session that was conducted by Mr. Vinay Pawar on 24 September, 2023.

The answers to the 'True or False' questions asked are as follows:  

| Q.No. | Question | ANSWER |
|-----| ------------|------------|     
| 01 | PostgreSQL is an example of an RDBMS (Relational Database Management System). | True |
| 02 | PostgreSQL is known for features such as ACID compliance, extensibility, and high performance. | True |
| 03 | In PostgreSQL, a database is a collection of related tables. | True |
| 04 | A SELECT statement is used to retrieve data from a PostgreSQL table. | True |
| 05 | SQL queries can be used to modify data in a PostgreSQL database, including inserting, updating, and deleting records. | True |
| 06 | NOT NULL constraints cannot be applied to columns in PostgreSQL. | False |
| 07 | Unique constraints ensure that values in a column are unique across all records in a table. | True |
| 08 | CHECK constraints allow you to specify custom rules for data validation. | True |
| 09 | Data types in a database define the kind of values that can be stored in a column, such as integers, text, or dates. | True |
| 10 | Foreign keys are used to establish relationships between tables by referencing the primary key of another table. | True |

--------------------------------------------------------------
