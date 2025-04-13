Data Definition Language (DDL)
Data Manipulation Language (DML)
Data Control Language (DCL)
Transactional Control Language (TCL)

## DDL: (C A T Comment Rename Drop)
* CREATE: to create a database and its objects like (table, index, views, store procedure, function, and triggers)
* ALTER: alters the structure of the existing database
* DROP: delete objects from the database
* TRUNCATE: remove all records from a table, including all spaces allocated for the records are removed
* COMMENT: add comments to the data dictionary
* RENAME: rename an object

## DML: (U S I D M C L)
* SELECT: retrieve data from a database
* INSERT: insert data into a table
* UPDATE: updates existing data within a table
* DELETE: Delete all records from a database table
* MERGE: UPSERT operation (insert or update)
* CALL: call a PL/SQL or Java subprogram
* EXPLAIN PLAN: interpretation of the data access path
* LOCK TABLE: concurrency Control

## DCL: 
GRANT: grant permissions to the user for running DML(SELECT, INSERT, DELETE,…) commands on the table
REVOKE: revoke permissions to the user for running DML(SELECT, INSERT, DELETE,…) command on the specified table

## TCL:
Roll Back: Used to cancel  or Undo changes made in the database 
Commit: It is used to apply or save changes in the database
Save Point: It is used to save the data on the temporary basis in the database


