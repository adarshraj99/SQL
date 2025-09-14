#### Primary Key: 
Used to Keep data unique eg: emp_id . It is to avoid duplicate data entry in table. 
Can make a column as primary key while making table:
```
Create table <empoyees>
(name varchar(20),    # If name is >20. extra words will get `truncated`. 
emp_id int not null,  # Primary key should not be null
emp_pay double,
Primary key (emp_id)
)
```

#### Auto Increment:
To automatcally increment the primary key value. ex:
```
Create table <empoyees>
(name varchar(20),
emp_id int not null Auto Increment,
emp_pay double,
Primary key (emp_id)
)
```

#### Default: 
To put default value if any value is not given while inserting the data.
```
create table emp
(
name varchar(20) not null default 'default name',
age int not null default 00,
pay double
);
```


Can also alter table to make an already available key as primary key:
```
ALTER TABLE empoyee_details
ADD PRIMARY KEY (emp_id);
```
If column contains NULL values and duplicates, Then first remove duplicates, update nulls,  set default to not null.

#### To see warnings: 
`set sql_mode = ''; ` Then after warning ,use : `show warnings;`
 
## Database Administration commands: 
#### SHOW :
`SHOW table <table name>;`

`SHOW tables;`

`SHOW databases;` : To see all the databases  

`USE <database name>;` : To start using the database.

`DESC <table name>` or `show columns from <table_name>` : To get all columns details from a table.

What show tables will return if there is no table ?  Ans:  Empty set.

 
## MySQL command line commands:
system cls : To clear terminal
\c : come out of SQL query



## DDL statement :
Data definition laguage. Used to define data in SQL. 

There are 5 DDL SQL commands: 
#### CREATE : 
To create database, tables, triggers, and other objects. 

syntaxes: 
To create DB: Create Database Database_name
To create Table: 
```
CREATE TABLE Table_name
(
Roll_No. Int ,    
First_Name Varchar (20) ,    
Last_Name Varchar (20) ,    
Age Int ,  
Marks float , 
);
```

#### DROP : 
#### ALTER : 
#### TRUNCATE : 
#### RENAME :  
#### COMMENT:



## DML :
Data Manipulation Language. 

#### UPDATE: 
#### SETECT: 
#### INSERT: 
#### DELETE: 
#### MERGE: 
#### CALL: 
#### LOCK TABLE: 
