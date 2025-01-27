Syllabus:
<img width="236" alt="image" src="https://github.com/user-attachments/assets/cb765389-a5ab-43ad-b1c3-77a445dd6dab" />


- after writing a syntax language does checks: 
syntax check -> availablity of these tables -> user accesses.
Symantic :

- Index use: Index is usefull as whole table not to retrive ,only particular index is nedded to get to make output.
- Metadata: SQL metadata don't have any data other than table structure.


-Create table:
create table sales2 as select * from table sales;
-select :
select segnamnt name , bytest/1024/1024 mb, from user segment where segment name='Sales2'
- exec command:
- Cardinality : division of num of distinct values by total number of values. If it is near to 1, it is not much repeating. 
-Statistics:
-Histogram: It will chk which table will have how much channel ids. 
-Selectivity:
-Squewed data: When data is equally distribued across database .It is called performance issue. It depends on cardinality.



Index ,uses, need


Nested Loop Join vs. Hash Join
#### Nested Loop Join:

Process: Iterates through each row of the outer table and for each row, iterates through each row of the inner table.
Efficiency: Best for small tables or when the join condition is highly selective.
Memory Usage: Generally low, as it doesn't require additional memory structures.
Performance: Can be slow for large tables due to the high number of comparisons.
#### Hash Join:

Process: Uses a hash table to match rows from the two tables based on the join key.
Efficiency: More efficient for large tables, especially when the join keys are well-distributed.
Memory Usage: Requires memory to build the hash table.
Performance: Typically faster than nested loop joins for large datasets.
