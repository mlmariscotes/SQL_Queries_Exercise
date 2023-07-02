## Retrieve everything from a table
How can you retrieve all the information from the cd.facilities table?
![image](https://github.com/mlmariscotes/SQL_Queries_Exercise/assets/99033220/312da78b-01e7-476d-a078-14f7ffacd44c)

#### My Solution
```SQL
SELECT * FROM cd.facilities
```

The SELECT statement is the basic starting block for queries that read information out of the database. A minimal select statement is generally comprised of select [some set of columns] from [some table or group of tables].

In this case, we want all of the information from the facilities table. The from section is easy - we just need to specify the cd.facilities table. 'cd' is the table's schema - a term used for a logical grouping of related information in the database.

Next, we need to specify that we want all the columns. Conveniently, there's a shorthand for 'all columns' - *. We can use this instead of laboriously specifying all the column names.
