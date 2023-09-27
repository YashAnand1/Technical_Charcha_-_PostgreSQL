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

On my system, the installation of Postgres was done using this [YouTube Tutorial](https://www.youtube.com/watch?v=-LwI4HMR_Eg). The steps followed for the setting-up Postgres were as follows: 
- Updating the system repositories using **`sudo apt update`**
- Installing PostgresSQL & additional utilities using **`sudo apt-get install postgresql postgresql-contrib`**
- Checking the status of Postgres using **`service postgresql status`**
- Entering Postgres using **`sudo su postgres`**
- Launching PSQL terminal for interacting with the database using **`psql`**
- Creating user with **`CREATE USER yashanand WITH PASSWORD 'a';`**
- Adding Superuser privilege to the new user using **`ALTER USER yashanand WITH SUPERUSER;`**

For reference, the output of the steps above can be viewed as an [image here]() and as a short video below:
[![IMAGE_ALT](https://img.youtube.com/vi/LwI4HMR_Eg/0.jpg)](https://www.youtube.com/watch?v=-LwI4HMR_Eg)


--------------------------------
<center>

## PostgreSQL: Q&A    

</center>

After gaining a basic understanding and a working set-up of Postgres, I worked on giving answers to the 'True or False' questions as a part of our first assignment. These questions were based on the 'Technical Charcha On PostgreSQL' session that was held on 24 September, 2023.

The answers to the questions asked are as follows:        
| Q.No. | Question | ANSWER |
|-----| ------------|------------|     
| 1 | | |


